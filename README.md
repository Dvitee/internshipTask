# 🎵 Music Genre Classification Using CNN

This project implements a deep learning model to classify audio files into music genres using Convolutional Neural Networks (CNNs). Built using the GTZAN dataset, it also features a demo where users can upload audio files and receive genre predictions with confidence scores.

---

## 📌 Overview

- **Objective**: Predict the genre of music from an input audio file.
- **Technologies**: Python, Librosa, Keras, TensorFlow, NumPy, Scikit-learn.
- **Dataset**: [GTZAN Genre Collection](http://marsyas.info/downloads/datasets.html) - 1,000 audio tracks across 10 genres.

---

## 📁 Dataset Structure

Ensure your GTZAN dataset is placed in this structure:

Data/
└── genres_original/
├── blues/
├── classical/
├── country/
├── disco/
├── hiphop/
├── jazz/
├── metal/
├── pop/
├── reggae/
└── rock/

yaml
Copy
Edit

You can extract the dataset from a `.zip` and place it in your Google Drive for Colab access.

---

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/music-genre-classification.git
   cd music-genre-classification
Install dependencies:

bash
Copy
Edit
pip install librosa numpy scikit-learn tensorflow
Open the notebook in Google Colab and run the cells step-by-step:

Mount Google Drive

Set the dataset path

Extract MFCC features

Train CNN model

Upload audio files for prediction

🧪 Example Prediction Output
After uploading an audio file, the notebook returns:

yaml
Copy
Edit
🎶 Predicted Genre: hiphop (100.00% confidence)
🎶 Predicted Genre: classical (87.08% confidence)
🎶 Predicted Genre: metal (37.02% confidence)
🎶 Predicted Genre: hiphop (99.86% confidence)
🧠 Model Overview
Model: Convolutional Neural Network (CNN)

Input: MFCC features extracted from 30-second audio samples

Output: One of 10 music genres

Training Accuracy: 82.81%

Validation Accuracy: 36.50%

Model shows overfitting — room for improvement using regularization and augmentation.

🛠 Features
🎧 MFCC feature extraction

🧠 CNN-based classification

📊 Accuracy and loss visualizations

📁 Upload your own audio files for prediction

🎼 Confidence score for predicted genre
