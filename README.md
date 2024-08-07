# Speech Emotion Recognition and Sound Classification

## Overview

The **Speech Emotion Recognition and Sound Classification** project aims to classify emotions from speech signals and categorize various sounds into predefined classes. This machine learning project leverages advanced algorithms and techniques in audio processing to achieve high accuracy in recognizing and classifying emotions from speech, as well as identifying different types of sounds.

# Dataset Information

There are a set of 200 target words which were spoken in the carrier phrase "Say the word _' by two actresses (aged 26 and 64 years) and recordings were made of the set portraying each of seven emotions (anger, disgust, fear, happiness, pleasant surprise, sadness, and neutral). There are 2800 data points (audio files) in total.

The dataset is organised such that each of the two female actor and their emotions are contain within its own folder. And within that, all 200 target words audio file can be found. The format of the audio file is a WAV format

### Output Attributes
- anger
- disgust
- fear
- happiness
- pleasant surprise
- sadness
- neutral

**Download link:** https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess
**More Datasets:** https://www.kaggle.com/dmitrybabko/speech-emotion-recognition-en


## Features

- **Emotion Recognition**: Detects and classifies emotions such as happiness, sadness, anger, and surprise from audio recordings of speech.
- **Sound Classification**: Identifies and categorizes various non-speech sounds into predefined classes (e.g., environmental sounds, mechanical noises).
- **Preprocessing**: Includes audio feature extraction techniques such as Mel-Frequency Cepstral Coefficients (MFCCs) and spectrograms.
- **Model Training**: Utilizes machine learning models like Convolutional Neural Networks (CNNs) and Recurrent Neural Networks (RNNs) for classification tasks.
- **Evaluation**: Provides performance metrics such as accuracy, precision, recall, and F1-score for both emotion recognition and sound classification tasks.
Achieved Validation accuracy of 72.32%

## Requirements

- Python 3.7+
- Libraries: TensorFlow, Keras, librosa, NumPy, pandas, scikit-learn

## Acknowledgements
- **Librosa** for audio processing
