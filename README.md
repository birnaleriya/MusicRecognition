# 🎶 AuralSense

**A Deep Learning-Based System for Detecting Emotions from Music Tracks**

---

## 🌟 Project Overview

AuralSense is an intelligent system that automatically classifies the emotional content of music tracks. By leveraging audio signal processing and deep learning, the system detects emotions like **Happy**, **Sad**, **Angry**, and **Relaxed**, based on music features.

This project contributes to mood-aware apps, intelligent recommendation engines, and enhancing user experience in music platforms.

---

## 🚀 Key Features

- 🎵 Automatic Emotion Detection from audio tracks  
- 🎵 Multi-class classification: *Happy, Sad, Angry, Relaxed*  
- 🎵 Deep Learning with CNN for feature extraction and LSTM for temporal learning  
- 🎵 Audio feature extraction using Mel Spectrograms, MFCCs, etc.  
- 🎵 Support for expanding emotion categories  
- 🎵 Potential for real-time emotion analysis  

---

## 🛠️ Tech Stack & Tools

| Technology        | Purpose                                 |
|-------------------|------------------------------------------|
| Python            | Core programming language               |
| Librosa           | Audio processing and feature extraction |
| NumPy, Pandas     | Data handling and preprocessing         |
| Matplotlib, Seaborn | Visualizations                        |
| TensorFlow / Keras | Deep Learning model development       |
| Scikit-learn      | Evaluation metrics and preprocessing    |
| Jupyter Notebooks | Experimentation and prototyping         |

---

## 🎯 Model Details

- **CNN layers** extract spatial features from Mel Spectrograms  
- **LSTM layers** capture temporal dynamics of music sequences  
- **Softmax classifier** performs multi-class emotion prediction  

**Input Features Include:**

- Mel Spectrograms  
- MFCCs  
- (Optional) Chroma Features  

---

## 📊 Evaluation Metrics

- ✅ Accuracy  
- ✅ Confusion Matrix  
- ✅ Precision, Recall, F1-Score  
