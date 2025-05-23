# 🎵 Music Genre Classification with CNN

This project uses deep learning to classify music genres using the GTZAN dataset and a Convolutional Neural Network (CNN). It includes a Colab demo where users can upload audio files and receive predicted genres with confidence scores.

## 📂 Dataset

We use the [GTZAN dataset](https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification?resource=download) consisting of 100 audio files for each of 10 genres:  
`blues`, `classical`, `country`, `disco`, `hiphop`, `jazz`, `metal`, `pop`, `reggae`, `rock`

```
Data/
└── genres_original/
    ├── blues/
    ├── classical/
    └── ...
```

## 🔧 Features

- MFCC feature extraction using `librosa`
- CNN model using `Keras`
- 80/20 train-validation split
- Upload and predict genre of MP3/WAV files
- Shows genre with confidence score

## 🧠 Model Performance

- **Training Accuracy**: 82.81%  
- **Validation Accuracy**: 36.50%  
- ✅ Working upload prediction demo

Example:
```
🎶 Predicted Genre: hiphop (100.00% confidence)
```

## 🚀 How to Run

1. Mount your Google Drive in Colab
2. Place the dataset inside `/MyDrive/Data/genres_original/`
3. Open and run `mgc.ipynb`
4. Upload a test audio file and run the prediction cell

## 🧪 Tools & Libraries

- Python
- Librosa
- NumPy, Pandas
- TensorFlow / Keras

## 📈 Future Improvements

- Reduce overfitting with regularization or more data
- Add spectrogram-based CNN
- Build a web-based front-end (e.g., Streamlit or Flask)



---

**Author**: Dviteesha Salgaonkar 
GitHub: [@dvitee](https://github.com/dvitee)
