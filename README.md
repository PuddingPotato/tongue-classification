# Tongue Classification with Convolution Neural Network

This project focuses on classifying tongue health conditions using convolutional neural networks (CNNs). The characteristics of the tongue are important indicators of oral hygiene and can reflect underlying illnesses. Early identification of abnormal tongue features allows individuals to seek timely medical advice for proper diagnosis.

---

## 🎯 Objective

To develop machine learning models capable of classifying tongue images into different health conditions. The models aim to assist in early detection of potential oral and systemic health issues by analyzing tongue appearances.

---

## 🛠️ Tools & Technologies

- **Convolutional Neural Networks (CNNs)** – For deep learning-based image classification  
- **Python** – Core implementation language  
- **TensorFlow / Keras** – For building and training CNN models  
- **Roboflow, Kaggle, Google Images** – Sources for tongue image datasets  
- **Data Augmentation** – Techniques like flipping, rotation, and scaling to enhance data diversity

---

## 🧠 Key Features

- **Two-Stage Classification Models**  
  - **Model 1**: Classifies between **normal** and **abnormal** tongue conditions  
    - Dataset split: 57% training, 18% validation, 25% testing  
    - Achieved **96.49% accuracy**
  - **Model 2**: Classifies among **black hairy tongue**, **cancer-risk tongue**, and **diabetes-risk tongue**  
    - Dataset split: 54% training, 18% validation, 28% testing  
    - Achieved **86.17% accuracy**

- **Data Augmentation**  
  - Performed to improve model robustness and handle limited data availability.

- **Evaluation Results**  
  - Graphs showing training and testing performance (accuracy and loss curves) are available in the `evaluations` folder within each model directory (`model 1`, `model 2`).

---

## 📂 Dataset Sources

- Roboflow
- Kaggle
- Google Search (filtered for relevant medical images)

---

## 🖼️ Example Output

- Classification labels:  
  - Normal  
  - Abnormal (black fur, cancer risk, diabetes risk)

- Performance graphs:  
  - Accuracy vs Epochs  
  - Loss vs Epochs

---

## 🚀 Future Improvements

- Expand dataset with more diverse and higher-quality medical images
- Explore transfer learning with pretrained models to further boost accuracy
- Deploy as a mobile or web application for real-time tongue health screening
