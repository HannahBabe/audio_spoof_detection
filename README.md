# audio_spoof_detection

(working) Project Title: DeepFake audio detection using deep learning

Author: Hannah Babe

Description: 
In this project I am planning to use the Spoofing-Aware Speaker Verification (SASV) 2019 dataset and use several example models, such as the one developed by Dessa (https://github.com/dessa-oss/fake-voice-detection), as a baseline to generate my own spoofed audio detection model. I have found that the Spoofing-Aware Speaker Verification (SASV) 2019 to be extensive, but I have also found another dataset of partially spoofed audio as well (https://paperswithcode.com/dataset/partialspoof) that was generated from the origional SASV 2019 dataset. I found a completely seperate dataset of generated audio clips as well as pre-trained models on this site: https://github.com/rub-syssec/wavefake, which I am also planning on using for help in building my model, and as a potential second dataset. The idea for this project came partially after I read this article on Medium: https://medium.com/dessa-news/detecting-audio-deepfakes-f2edfd8e2b35, written by Dessa. 

Preprocessing: So far what I have read is that it is easier to detect generated audio in ML when the audio files are converted to spectrograms. Therefore I have converted the x_train and x_eval datasets which were origionally flac files into spectrograms with an associated file name for identification in the y_train and y_eval files which identify the spoof and real audio. One issue I have come across is that the files containinf the .flac files used to create x_train and x_eval are massive, containing over 25,000 files. This makes manipulation of the files very time consuming, which is why I have also attempted to save x_train and x_eval in local storage in my Google Drive. 

Additional Notes: I was origionally planning on working alone for this project. However Alessandra and I realized we were both without partners for this project, and are thinking of working together. However we decided to submit initally two different proposals in order to get feedback on which project seems more fesible in the time contraints we have.
