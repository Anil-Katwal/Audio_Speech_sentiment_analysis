# Audio Sentiment Analysis Using Deep Learning (CNN)
## Overview
This project implements an audio sentiment analysis system using Convolutional Neural Networks (CNN). The system processes audio input files, extracts features using librosa, and predicts the sentiment (e.g., positive, negative, neutral) expressed in the speech/audio. The backend is built with Flask to provide a simple web interface for uploading audio files and displaying sentiment predictions.
Features
Audio feature extraction with librosa (MFCCs, etc.)

Deep learning model based on TensorFlow/Keras CNN architecture

Flask-based web app for easy file upload and sentiment prediction

Handles various audio formats (WAV, MP3, etc.)

Supports real-time prediction on uploaded audio
## Setup Instructions
### Prerequisites
Python 3.7 or higher
pip package manager

### Project Structure
Audio-Sentiment-Analysis-Using-Deep-Learning-CNN/
│
├── main.py                  # Flask app entry point
├── requirements.txt         # Python dependencies
├── sentiment_cnn_model.h5   # Pre-trained TensorFlow model file
├── inputs/                  # Sample input audio files
├── templates/               # HTML templates for Flask
├── uploads/                 # Folder to store uploaded audio files
├── le.pkl                   # Label encoder for sentiment classes
└── README.md                # This file

## Contact
For questions or collaboration, reach out to Anil Katwal at [aniljungkatwal@gmail.com].