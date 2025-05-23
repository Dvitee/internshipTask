🎵 Music Genre Classification Using CNN
This project implements a deep learning approach to automatically classify audio files into music genres using Convolutional Neural Networks (CNNs). It uses the GTZAN dataset and provides a working demo for genre prediction from uploaded audio files.

📌 Overview
🎯 Goal: Predict the genre of a given audio track.

🛠️ Technologies Used: Python, Librosa, Keras (TensorFlow backend), NumPy, Scikit-learn.

📁 Dataset: GTZAN Genre Collection – 1,000 audio files, 10 genres.

🔍 Features
Audio feature extraction using MFCCs.

CNN-based classification model.

Upload & predict audio genre with confidence score.

Real-time audio prediction demo.

Optionally visualize spectrograms (not implemented by default).

📂 Dataset Structure
Ensure the genres_original folder is extracted and structured like this:

Copy
Edit
Data/
└── genres_original/
    ├── blues/
    ├── classical/
    ├── country/
    ├── ...
🚀 How to Run
Mount Google Drive in Google Colab:

python
Copy
Edit
from google.colab import drive
drive.mount('/content/drive')
Set the dataset path:

python
Copy
Edit
dataset_path = "/content/drive/MyDrive/Data/genres_original"
Extract MFCC features and train the CNN model.

Upload and predict audio genre:

python
Copy
Edit
from google.colab import files
uploaded = files.upload()
✅ Example Prediction Output
yaml
Copy
Edit
🎶 Predicted Genre: hiphop (100.00% confidence)
🎶 Predicted Genre: classical (87.08% confidence)
📊 Model Performance
Training Accuracy: 82.81%

Validation Accuracy: 36.50%

Issue: Overfitting due to small dataset size.

📈 Possible Improvements
Use larger or augmented dataset.

Apply regularization or advanced architectures.

Implement spectrogram visualization.

📝
