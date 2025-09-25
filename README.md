# 🎤 Real-Time Emotion Recognition from Speech

This project implements a **real-time speech emotion recognition system** using deep learning.  
It leverages **Convolutional Neural Networks (CNNs)** and **Long Short-Term Memory (LSTM)** networks to classify emotions such as *neutral, calm, happy, sad, angry, fearful, disgusted,* and *surprised* from audio inputs.  

The system is designed for **low-latency applications** like interactive voice response systems, customer service bots, and mental health monitoring tools.

---

## Features
- Real-time audio emotion classification
- Hybrid **CNN + LSTM architecture** for spectral + temporal feature learning
- Data preprocessing: silence removal, normalization
- Feature extraction: MFCCs, Chroma, Mel-Spectrograms
- Data augmentation: noise injection, pitch shifting, time stretching
- Evaluation with **accuracy, precision, recall, F1-score, and confusion matrix**
- Achieved **~95% accuracy** on the RAVDESS dataset

---

## Dataset
- **RAVDESS (Ryerson Audio-Visual Database of Emotional Speech and Song)**
- Contains recordings of 24 professional actors expressing 8 emotions
- Used for training, validation, and testing

---

## Tech Stack
- **Python**
- **TensorFlow / Keras**
- **Librosa** (audio preprocessing & feature extraction)
- **NumPy, Pandas, Matplotlib** (data handling & visualization)

---
