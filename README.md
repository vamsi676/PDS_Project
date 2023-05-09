# PDS_Project_(DATA SHIELDERS)

## Readme
## Introduction
This code loads a dataset of speech recordings from the TESS (Toronto emotional speech set) database and performs data analysis on it. The dataset consists of 2800 speech recordings classified into 7 categories based on emotions: angry, disgust, fear, happy, neutral, ps, and sad. The code uses the librosa library to visualize waveplots and spectrograms of the audio recordings and also plays the audio recordings.

## Requirements
pandas
numpy
os
sklearn.preprocessing.OneHotEncoder
seaborn
matplotlib.pyplot
librosa
librosa.display
IPython.display.Audio
warnings
## Dataset
The dataset used in this code is from the TESS (Toronto emotional speech set) database. It consists of 2800 speech recordings classified into 7 categories based on emotions: angry, disgust, fear, happy, neutral, ps, and sad. The dataset is stored in the following directory: 'C:/Users/surya/OneDrive/Desktop/TESS Toronto emotional speech set data'.

## Technologies 
Technologies used in a speech emotion detection :

Natural Language Processing (NLP): NLP techniques can be used to analyze and interpret the emotions present in speech.

Machine Learning (ML) algorithms: ML algorithms can be trained on labeled datasets to detect patterns in speech that correspond to different emotions.

Deep Learning models: Deep Learning models such as Convolutional Neural Networks (CNNs) or Recurrent Neural Networks (RNNs) can be used to learn complex representations of speech data that capture emotional features.

Python programming language: Python is a popular language for machine learning and data analysis tasks and has numerous libraries and frameworks available for speech processing and emotion detection.

Speech processing libraries: Libraries such as SpeechRecognition, PyAudio, and librosa can be used for speech data processing, feature extraction, and speech-to-text conversion.

Data visualization libraries: Libraries such as Matplotlib and Seaborn can be used to visualize the results of the emotion detection models.

Cloud computing platforms: Cloud computing platforms such as Amazon Web Services (AWS) or Google Cloud Platform (GCP) can be used to store and process large speech datasets.

Open source libraries and frameworks: Open source libraries and frameworks such as TensorFlow, Keras, and PyTorch can be used to implement machine learning models for speech emotion detection.


## Code
The code first loads the dataset into the 'paths' and 'labels' lists.
Then, a dataframe is created to store the paths and labels.
Data analysis is performed by displaying the count of labels using a seaborn countplot.
The code defines two functions, 'waveplot' and 'spectrogram', to visualize waveplots and spectrograms of the audio recordings.
The code then loads audio recordings for each emotion, applies the 'waveplot' and 'spectrogram' functions, and plays the audio using IPython.display.Audio.
## How to Use
Ensure that the dataset is stored in the directory or change the directory in the code.
Install the required libraries.
Copy and paste the code into a Python IDE or Jupyter Notebook and run it.
## Acknowledgments
The TESS (Toronto emotional speech set) database was created by the University of Toronto.
