# Speech Emotion Recognition using CNN

This project implements speech emotion recognition using a Convolutional Neural Network (CNN) model.

## Description

The project uses deep learning techniques to classify emotions from speech audio. The system can recognize 5 different emotions:

- Angry
- Friendly
- Cold
- Happy
- Tired

## Processing Pipeline

1. **Data Preprocessing**:

   - Reading and processing WAV audio files
   - Audio data normalization

2. **Feature Extraction**:

   - Using MFCC (Mel-frequency cepstral coefficients) technique
   - Converting audio into features suitable for deep learning models

3. **CNN Model**:
   - Using Convolutional Neural Network architecture
   - Training the model for emotion classification

## System Requirements

Required libraries are listed in `requirements.txt`:

```
numpy==1.26.4
pandas==2.2.3
matplotlib==3.9.2
seaborn==0.13.2
librosa==0.10.2
tensorflow==2.18.0
keras==3.6.0
scikit-learn==1.5.2
```

## Installation

1. Clone the repository:

```bash
git clone [repository-url]
```

2. Install required libraries:

```bash
pip install -r requirements.txt
```

## Usage

1. Prepare labeled WAV audio data
2. Run `BuildModel.ipynb` to train the model
3. The model will be saved after training

## Main Project Structure

- `BuildModel.ipynb`: Main file containing data processing and model training code
- `requirements.txt`: List of required libraries
- `README.md`: Project documentation
