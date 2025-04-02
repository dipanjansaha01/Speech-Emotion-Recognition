# 🎤 Speech Emotion Recognition using LSTM

## 📌 Overview
Speech Emotion Recognition (SER) is a system that identifies human emotions from voice signals. This project leverages **Long Short-Term Memory (LSTM)** networks to analyze speech patterns and classify emotions based on extracted features.

---

## ✨ Features
✅ Preprocessing of audio signals  
✅ Feature extraction (MFCCs, Chroma, Mel Spectrograms)  
✅ LSTM-based deep learning model for emotion classification  
✅ Model evaluation and performance metrics  

---

## 📂 Dataset
📥 **Download Link:** [Toronto Emotional Speech Set (TESS)](https://www.kaggle.com/ejlok1/toronto-emotional-speech-set-tess)

### 📜 Dataset Information
- **Speakers:** 2 Female Actresses (aged 26 and 64)
- **Total Audio Files:** 2800 WAV files
- **Emotions Covered:**
  - 😠 Anger  
  - 🤢 Disgust  
  - 😨 Fear  
  - 😃 Happiness  
  - 😲 Pleasant Surprise  
  - 😢 Sadness  
  - 😐 Neutral  

---

## 🔍 Steps Involved
1️⃣ **Data Preprocessing:** Load and preprocess audio files.  
2️⃣ **Feature Extraction:** Extract **Mel-Frequency Cepstral Coefficients (MFCCs)** and other relevant features.  
3️⃣ **Model Training:** Train an **LSTM model** on the extracted features.  
4️⃣ **Evaluation:** Test the model and analyze **accuracy, precision, recall, and confusion matrix**.  

---

## 📊 Results
🎯 The trained model achieves an **accuracy of 97%** in classifying emotions from speech. Detailed evaluation metrics are available in the notebook.
