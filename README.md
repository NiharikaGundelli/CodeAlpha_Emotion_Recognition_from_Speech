# Emotion Recognition from Speech using Deep Learning

## Overview
This project builds a **speech emotion recognition system** using deep learning. The model classifies audio clips into 8 emotions: **neutral, calm, happy, sad, angry, fearful, disgust, and surprised**. It uses the RAVDESS dataset and combines CNN-LSTM architecture with attention mechanisms for robust performance.

---

## Features
✅ **Key Capabilities**:
- Processes raw audio files (WAV format)
- Extracts **MFCC features** for acoustic pattern recognition
- Uses **CNN-LSTM-Attention** architecture for temporal feature learning
- Real-time emotion prediction from microphone input
- 8-class classification with **75-85% accuracy**


## Dataset
- **RAVDESS**: 1,440 audio files from 24 actors (8 emotions)
- **Format**: 16-bit WAV files at 48kHz
- **Source**: [Kaggle RAVDESS Dataset](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio)

*Note: Dataset not included in repo due to licensing. Follow Kaggle link to download.*


## Requirements
```bash
python == 3.8+
tensorflow == 2.10
librosa == 0.9.2
numpy == 1.23
pandas == 1.5
matplotlib == 3.6
seaborn == 0.12
sounddevice == 0.4.6


