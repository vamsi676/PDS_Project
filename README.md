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
