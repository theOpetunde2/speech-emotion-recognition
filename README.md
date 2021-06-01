# speech-emotion-recognition
This is my Kaggle BIPOC final project.
The objective of this project is to build an automated emotion recognition for audio and speech files. This project is usable for:

1) customer care call centres to effectively analyse their calls, record the emotion that each call has so customers' level of satisfaction can be predicted based on the emotions from the calls.
customer order calls to identify if orders are urgent or not urgent based on the emotion that their voices carry
2) Policemen to automatically differentiate between fake callers and callers who are genuine and are in need of urgent help.

In this project, we will use the libraries librosa, soundfile, and sklearn (among others) to build a model using an MLPClassifier. This will be able to recognize emotion from sound files. We will load the data, extract features from it, then split the dataset into training and testing sets. Then, we’ll initialize an MLPClassifier and train the model. Finally, we’ll calculate the accuracy of our model.

The Dataset
For this Python mini project, we’ll use the RAVDESS dataset; this is the Ryerson Audio-Visual Database of Emotional Speech and Song dataset. This dataset has 7356 files rated by 247 individuals 10 times on emotional validity, intensity, and genuineness. The entire dataset is 24.8GB from 24 actors, but we’ve lowered the sample rate on all the files,
