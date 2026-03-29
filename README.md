# CSM-2025-26-BATCH-B-03
# 🤟  Sign Language Translator

Sign Language Recognition and Multilingual Translation System using Deep Learning.

## 📌 Project Overview

This project detects sign language gestures using a webcam and converts them into words.  
The detected word can be translated into multiple languages and spoken using text-to-speech.

The system uses **MediaPipe for hand landmark detection** and **TensorFlow deep learning model for gesture classification**.

---

## 🚀 Features

- Real-time gesture recognition
- Word-level sign language detection
- Multi-language translation
- Text-to-speech audio output
- Web interface using Flask
- Hand landmark detection using MediaPipe

---

## 🛠 Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- MediaPipe
- Flask
- NumPy
- Scikit-learn
- Deep Translator

---

## 📂 Project Modules

### 1. Data Collection
Collect hand gesture data using webcam and MediaPipe.

### 2. Model Training
Train deep learning model for gesture classification.

### 3. Gesture Prediction
Predict gestures in real-time using webcam input.

### 4. Translation
Convert recognized word into multiple languages.

### 5. Audio Output
Convert translated text into speech.

---

## ▶️ How to Run the Project

### Install Requirements

pip install -r requirements.txt

###Train Model
python train_model.py

###Run Application
python app.py

###Open browser:

http://localhost:5000
