# 🌸 Iris Flower Image Classification using CNN & TensorFlow

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge\&logo=python)
![TensorFlow](https://img.shields.io/badge/TensorFlow-DeepLearning-orange?style=for-the-badge\&logo=tensorflow)
![Keras](https://img.shields.io/badge/Keras-CNN-red?style=for-the-badge\&logo=keras)
![OpenCV](https://img.shields.io/badge/ComputerVision-AI-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-purple?style=for-the-badge)

</div>

---

# 📌 Project Overview

This project is a **Deep Learning based Image Classification System** that classifies Iris flower species using a **Convolutional Neural Network (CNN)** built with **TensorFlow** and **Keras**.

The model is trained on an image dataset containing three different Iris flower species:

* 🌿 Iris Setosa
* 🌿 Iris Versicolour
* 🌿 Iris Virginica

The CNN automatically learns flower patterns, petal structures, textures, and visual features directly from images.

---

# 🎯 Project Objectives

✅ Build a Deep Learning based image classifier
✅ Understand CNN architecture and image preprocessing
✅ Train a TensorFlow/Keras model on flower images
✅ Visualize training performance using graphs
✅ Evaluate model accuracy using classification metrics
✅ Save and deploy trained AI model

---

# 🧠 Deep Learning Concepts Used

| Concept              | Description                   |
| -------------------- | ----------------------------- |
| CNN                  | Convolutional Neural Network  |
| Image Classification | Predicting flower category    |
| TensorFlow           | Deep Learning framework       |
| Keras                | High-level API for TensorFlow |
| Data Augmentation    | Improves model generalization |
| Dropout              | Prevents overfitting          |
| Softmax              | Multi-class classification    |

---

# 🖼️ Dataset Structure

```text
dataset/
│
├── iris-setosa/
│   ├── image1.jpg
│   ├── image2.jpg
│   └── ...
│
├── iris-versicolour/
│   ├── image1.jpg
│   └── ...
│
└── iris-virginica/
    ├── image1.jpg
    └── ...
```

---

# 🏗️ Project Folder Structure

```text
CodeAlpha_Iris_Image_Classification/
│
├── dataset/
│   ├── iris-setosa/
│   ├── iris-versicolour/
│   └── iris-virginica/
│
├── notebook/
│   └── iris_cnn_classification.ipynb
│
├── graphs/
│   ├── accuracy_graph.png
│   ├── loss_graph.png
│   ├── confusion_matrix.png
│   └── sample_images.png
│
├── models/
│   └── iris_cnn_model.h5
│
├── outputs/
│
├── README.md
├── requirements.txt
└── venv/
```

---

# ⚙️ Technologies Used

<div align="center">

| Technology       | Purpose                 |
| ---------------- | ----------------------- |
| Python           | Programming Language    |
| TensorFlow       | Deep Learning Framework |
| Keras            | CNN API                 |
| NumPy            | Numerical Operations    |
| Matplotlib       | Data Visualization      |
| Seaborn          | Heatmaps & Graphs       |
| Jupyter Notebook | Development Environment |

</div>

---

# 🔥 CNN Architecture

```text
Input Image
     ↓
Conv2D Layer
     ↓
MaxPooling Layer
     ↓
Conv2D Layer
     ↓
MaxPooling Layer
     ↓
Conv2D Layer
     ↓
Flatten Layer
     ↓
Dense Layer
     ↓
Dropout Layer
     ↓
Softmax Output Layer
```

---

# 📷 Sample Dataset Images

<p align="center">
  <img src="graphs/sample_images.png" width="700">
</p>

---

# 📊 Model Training Accuracy

<p align="center">
  <img src="graphs/accuracy_graph.png" width="700">
</p>

---

# 📉 Model Loss Graph

<p align="center">
  <img src="graphs/loss_graph.png" width="700">
</p>

---

# 🔍 Confusion Matrix

<p align="center">
  <img src="graphs/confusion_matrix.png" width="700">
</p>

---

# 📈 Model Performance

| Metric              | Result                   |
| ------------------- | ------------------------ |
| Training Accuracy   | 95%+                     |
| Validation Accuracy | 90%+                     |
| Loss Function       | Categorical Crossentropy |
| Optimizer           | Adam                     |

---

# 🚀 Features of This Project

✨ Deep Learning based Image Classification
✨ CNN architecture using TensorFlow/Keras
✨ Automatic image preprocessing
✨ Dataset normalization
✨ Validation split handling
✨ Accuracy & Loss visualization
✨ Confusion matrix evaluation
✨ Model saving using `.h5` format
✨ Professional project structure

---

# 🧪 Model Training

The model was trained using:

```python
model.fit(
    train_data,
    validation_data=validation_data,
    epochs=15
)
```

---

# 💾 Saved Model

The trained model is stored inside:

```text
models/iris_cnn_model.h5
```

This model can later be used for:

* Real-time prediction
* Deployment
* Flask web app
* Streamlit AI app

---

# 📚 Future Improvements

🔹 Increase dataset size
🔹 Apply data augmentation
🔹 Use Transfer Learning (MobileNet, ResNet)
🔹 Build a real-time prediction web app
🔹 Deploy model on cloud platforms
🔹 Improve accuracy with advanced CNN architectures

---

# 🌍 Real World Applications

🌸 Botanical Research
🌱 Smart Agriculture
📷 AI-based Plant Identification
🤖 Computer Vision Systems
📚 Educational AI Projects

---

# ▶️ How to Run This Project

## 1️⃣ Clone Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

---

## 2️⃣ Open Project Folder

```bash
cd CodeAlpha_Iris_Image_Classification
```

---

## 3️⃣ Create Virtual Environment

```bash
python -m venv venv
```

---

## 4️⃣ Activate Virtual Environment

### Windows

```bash
venv\Scripts\activate
```

---

## 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 6️⃣ Run Jupyter Notebook

```bash
jupyter notebook
```

---

# 👨‍💻 Author

## Jainam Khetani

🎓 B.Tech CSE Student
💡 Passionate about AI, Machine Learning & Development
🚀 Exploring Deep Learning & Computer Vision

---

# 📌 Internship Information

This project was developed as part of the **CodeAlpha Data Science Internship Program**.

---

# ⭐ Conclusion

This project demonstrates the implementation of a **Deep Learning based CNN model** for multi-class Iris flower image classification.

The project helped in understanding:

* CNN architecture
* Image preprocessing
* Deep learning workflows
* TensorFlow/Keras implementation
* Model evaluation techniques

---

<div align="center">

# 🌸 Thank You 🌸

If you like this project, consider giving it a ⭐ on GitHub!

</div>
