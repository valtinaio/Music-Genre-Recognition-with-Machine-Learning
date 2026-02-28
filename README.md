# Music-Genre-Recognition-with-Machine-Learning
Using different machine learning algorithms (Logistic Regression, Random Forest, SVM,...) to recognize different music genres.

## Overview
This project implements a Machine Learning pipeline to classify music genres based on audio features. The system analyzes raw audio waveforms and predicts the genre (e.g., Rock, Jazz, Hip-Hop) by extracting key acoustic characteristics.

## Key Features
- **Data Loading:** Seamless integration with Hugging Face `datasets` to load audio data.
- **Feature Extraction:** Extracts meaningful audio features using `librosa`:
  - **MFCCs (Mel-frequency cepstral coefficients):** Capture the timbral texture of the sound.
  - **Spectral Centroid:** Indicates the "brightness" of a sound.
  - **Zero Crossing Rate:** Useful for distinguishing percussive sounds.
- **Machine Learning:** Trains a classifier (e.g., Random Forest/SVM) to predict genres.
- **Evaluation:** Visualizes performance using Confusion Matrices and Accuracy scores.

## Dataset
The project uses the audio_data dataset containing 1230 audio samples of different music genres.

## Usage
The ipynb in this repository provides an experimentative example of a typical workflow for such projects. No final package is provided.

## Requriments
See requirements.txt
