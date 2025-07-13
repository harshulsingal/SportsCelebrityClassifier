# 🏆 Sports Celebrity Image Classification

This project focuses on identifying sports celebrities from images using classical computer vision and machine learning techniques. It combines OpenCV for image preprocessing, Wavelet Transforms for feature extraction, and an SVM model for classification.

---

## 📌 Features

- ✅ Image classification of multiple sports celebrities.
- 🖼️ Uses OpenCV for face detection and image processing.
- 🌊 Wavelet Transforms used for advanced feature extraction.
- 🤖 Trained with Support Vector Machine (SVM) for classification.
- 🔍 Hyperparameter tuning with GridSearchCV for best accuracy.

---

## 🛠️ Tech Stack

- Python 🐍
- OpenCV 🧠
- Scikit-learn 🔬
- NumPy 📊
- Matplotlib (for visualization) 📈

---

## 🚀 How It Works

1. **Face Detection**  
   Images are processed using OpenCV’s Haar Cascades to detect and crop faces of celebrities.

2. **Feature Extraction**  
   Two feature sets are used:
   - Raw pixel data (resized face images)
   - Wavelet transformed features (for frequency domain representation)

3. **Model Training**  
   Features are fed into an SVM model, which is fine-tuned using `GridSearchCV` for optimal hyperparameters.

4. **Prediction**  
   Given a new image, the model classifies it into one of the known sports celebrities.


