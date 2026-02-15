# PRODIGY_ML_05
# 🍔 Food Recognition & Calorie Estimation System

## 📌 Overview

This project presents a deep learning-based system that recognizes food items from images and estimates their calorie content.  
It helps users track dietary intake and make informed nutritional decisions.

The model is trained using the Food-101 dataset and leverages transfer learning for improved accuracy and performance.

---

## 🎯 Key Features

- 📸 Food image classification (101 categories)
- 🧠 Transfer learning using MobileNetV2
- 🔥 Calorie estimation based on predicted class
- 📊 Performance evaluation (Accuracy & Confusion Matrix)

---

## 🧠 Model Architecture

Input Image (224x224)  
↓  
Pretrained CNN (Feature Extraction)  
↓  
Global Average Pooling  
↓  
Dense Layer (ReLU)  
↓  
Softmax Output (101 Classes)

---

## 📊 Dataset

- Food-101 Dataset  
- 101 food categories  
- 101,000 images  
- Balanced distribution  

---

## 🛠️ Technologies Used

- Python  
- TensorFlow / Keras  
- TensorFlow Datasets  
- NumPy  
- Matplotlib  
- Scikit-learn  

---

## 📈 Model Performance

- Transfer learning approach  
- Fine-tuning applied  
- Evaluated using classification metrics (Accuracy, Precision, Recall, F1-score)

---

## 🚀 Future Enhancements

- Portion size estimation  
- Multi-food detection  
- Depth-based calorie calculation  
- Personalized dietary tracking  

---

## 👨‍💻 Author

Amogh Waskar
