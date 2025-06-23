# 🎵 Music Genre Classifier

This project builds a **music genre classification model** using machine learning. It uses extracted audio features (like tempo, rhythm, and spectral properties) to predict the genre of a track. The notebook includes data preprocessing, feature analysis, model training, and evaluation.

---

## 🧠 Objectives

- Understand and clean audio feature data
- Perform exploratory data analysis on features by genre
- Train multiple classification models to predict music genre
- Evaluate model performance using accuracy and confusion matrix

---

## 📊 Dataset Features

The dataset includes audio-based numerical features such as:

- Spectral Centroid, Zero Crossing Rate, Chroma STFT
- MFCCs (Mel Frequency Cepstral Coefficients)
- Tempo, Beat, and Energy
- Label: Genre (`rock`, `classical`, `pop`, etc.)

---

## 🤖 ML Models Used

- Logistic Regression
- K-Nearest Neighbors
- Decision Trees
- Random Forest

Model performance is evaluated using accuracy, confusion matrix, and cross-validation.

---

## 🧰 Libraries Used

- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- Librosa


---

## 🚀 How to Run

1. Clone the repository or download the notebook.
2. Install dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn scikit-learn librosa

