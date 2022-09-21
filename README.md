Bowel Sound Detector Web App

Get number of bowel sounds from audio file.

The Bowel Sound detector app uses a deep learning CRNN model to predict the number of bowel sounds from an audio file!

The WebApp is deployed using streamlit.

Demo

To view the Web API you can access this link

https://tuggypetu-num-bowel-sounds-app-tu4yim.streamlitapp.com/

Screenshot 2022-09-20 at 8 53 02 AM

To use the Web app, firstly, you need to upload an audio file. That's it! Let the progam do its thing!

The Web app will load the audio file, will plot the spectrogram of the audio file,

And finally, will load the number of bowel sounds in the audio file.

It takes less than a minute!

Run Locally

To load the project on your IDE, open terminal and enter,

git clone https://github.com/tuggypetu/num_bowel_sounds.git
Next, install pip if not already installed, and install the requirements from the requirements file

pip install -r requirements.txt
After requirements downloaded, to view the Web API on local or network browser,

streamlit run app.py
Authors

Siddhanth Biswas
Chen Zhang
Acknowledgements

(Ficek et al., 2021)
librosa documentation
