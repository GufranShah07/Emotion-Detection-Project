# 🎙️ Emotion Detection Project

An **AI-based Speech Emotion Detection System** that analyzes human speech and predicts the underlying emotion from an audio recording.

The project uses **audio signal processing and machine learning/deep learning techniques** to extract meaningful features from speech and classify emotions.

---

## 📌 Project Overview

Human speech contains important emotional information such as tone, pitch, intensity, and frequency patterns.

This project aims to automatically recognize emotions from speech using an AI-based approach.

The system takes an audio input, processes the speech signal, extracts relevant audio features, and predicts the corresponding emotion.

### 🎯 Objectives

- Detect emotions from human speech.
- Preprocess and analyze audio signals.
- Extract meaningful speech features.
- Train a machine learning/deep learning model.
- Classify speech into different emotional categories.
- Provide an easy-to-use application for emotion prediction.

---

## 🧠 Technologies Used

- **Python**
- **Machine Learning / Deep Learning**
- **Librosa** – Audio processing and feature extraction
- **NumPy** – Numerical computation
- **Pandas** – Data processing
- **Scikit-learn** – Machine learning utilities
- **TensorFlow / Keras** – Model development
- **Flask** – Web application
- **HTML/CSS** – User interface

---

## 🔊 Features

- 🎤 Speech/audio input
- 🎵 Audio preprocessing
- 📊 Feature extraction
- 🧠 AI-based emotion classification
- 🌐 Web-based interface
- ⚡ Fast emotion prediction
- 📈 Model training and evaluation

---

## 😊 Emotion Classes

Depending on the dataset used, the system can classify emotions such as:

- Angry
- Happy
- Sad
- Neutral
- Fear
- Disgust
- Surprise
- Calm

> The exact emotion classes depend on the dataset and trained model used in this project.

---

## ⚙️ System Workflow

```text
Audio Input
     ↓
Audio Preprocessing
     ↓
Feature Extraction
     ↓
MFCC / Audio Features
     ↓
Trained AI Model
     ↓
Emotion Classification
     ↓
Predicted Emotion
```

---

## 🎵 Feature Extraction

The project uses audio signal processing techniques to extract features from speech.

### MFCC

**Mel-Frequency Cepstral Coefficients (MFCCs)** are commonly used features for speech and audio analysis.

MFCCs represent the characteristics of the human voice in a way that is useful for machine learning models.

Other audio features can include:

- MFCC
- Chroma features
- Mel Spectrogram
- Zero Crossing Rate
- Spectral Centroid
- Spectral Bandwidth

---

## 📂 Project Structure

```text
Emotion-Detection-Project/
│
├── app.py
├── train.py
├── index.html
├── README.md
│
├── static/
│   ├── css/
│   └── js/
│
├── templates/
│
├── dataset/
│
├── model/
│
└── requirements.txt
```

> The actual folder structure may vary depending on the files included in the project.

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/GufranShah07/Emotion-Detection-Project.git
```

### 2. Navigate to the project directory

```bash
cd Emotion-Detection-Project
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

---

## 🏋️ Model Training

To train the emotion detection model:

```bash
python train.py
```

The training process includes:

1. Loading the speech dataset
2. Audio preprocessing
3. Feature extraction
4. Preparing training and testing data
5. Training the model
6. Evaluating model performance
7. Saving the trained model

---

## 🌐 Running the Application

Start the application using:

```bash
python app.py
```

The application will start a local web server.

Open the URL displayed in the terminal in your web browser.

---

## 📊 Model Evaluation

The model can be evaluated using metrics such as:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

These metrics help determine how effectively the model identifies different emotions.

---

## 💡 Applications

Speech emotion recognition can be useful in various fields:

- 🤖 Human-AI interaction
- 📞 Customer service analysis
- 🧠 Mental wellness applications
- 🎓 E-learning systems
- 🚗 Driver monitoring systems
- 📱 Voice assistants
- 🎮 Gaming
- 📞 Call-center analytics

---

## 🔮 Future Scope

The project can be further improved by:

- Using larger and more diverse speech datasets.
- Implementing advanced deep learning architectures.
- Using LSTM/RNN or Transformer-based models.
- Improving real-time emotion detection.
- Supporting multiple languages.
- Deploying the application online.
- Integrating real-time microphone input.
- Improving accuracy across different speakers and environments.

---

## 👨‍💻 Authors

**Gufran Shah**

Artificial Intelligence & Machine Learning

MIT Academy of Engineering, Pune

---

## 📜 License

This project is developed for **educational and
