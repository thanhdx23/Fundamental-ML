# Face Detection and Emotion Recognition Using Deep Learning

## 🚀 Overview  
This project focuses on building a **Deep Learning-based system** capable of:  

- Detecting human faces in images.  
- Classifying emotions into 7 categories:  
  - Angry  
  - Disgust  
  - Fear  
  - Happy  
  - Sad  
  - Surprise  
  - Neutral  

The system integrates advanced computer vision techniques and emotion recognition models to deliver accurate and efficient results.

---

## 🧠 Objective  
The goal was to develop a robust pipeline for **face detection** and **emotion recognition** leveraging state-of-the-art deep learning techniques.

---

## 🔧 Features  
- **Face Detection**: Utilized **Faster R-CNN** for detecting faces and extracting bounding boxes.  
- **Emotion Recognition**: Implemented a **TensorFlow/Keras-based emotion classifier** trained on preprocessed facial images.  
- **Preprocessing Steps**: Included resizing, normalization, and confidence threshold tuning to enhance model performance.  

---

## 📊 Results  
- Achieved precise face detection and emotion classification.  
- Obtained **59% validation accuracy** for the emotion classification model.  

---

## 🛠️ Techniques & Models  
### 1. Face Detection  
- **Framework**: Faster R-CNN.  
- **Output**: Bounding boxes for faces in the input images.  

### 2. Emotion Classification  
- **Framework**: TensorFlow/Keras.  
- **Preprocessing**:  
  - Resized images to ensure uniform input dimensions.  
  - Normalized pixel values for faster convergence.  
- **Model Architecture**: Fine-tuned deep learning model for emotion classification.  

### 3. Optimization  
- Tuned confidence thresholds to balance precision and recall.  
- Applied early stopping and learning rate scheduling during training.
