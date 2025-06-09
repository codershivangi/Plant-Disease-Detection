# 🌿 Plant Disease Detection using Deep Learning

This project uses **Convolutional Neural Networks (CNNs)** to detect and classify plant leaf diseases from images. The goal is to assist farmers and researchers in identifying diseases early and efficiently using deep learning models trained on image data.

![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow%2FKeras-red)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📁 Dataset

- **Source**: [PlantVillage Dataset](https://www.kaggle.com/emmarex/plantdisease)
- The dataset contains over 50,000 images of healthy and diseased plant leaves categorized into 38 classes.

---

## 🧠 Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- Jupyter Notebook

---

## 📌 Features

- Image preprocessing using OpenCV
- Data augmentation to improve generalization
- Convolutional Neural Network (CNN) for multi-class image classification
- Evaluation metrics: Accuracy, Loss, Confusion Matrix
- Trained model can predict diseases from uploaded leaf images

---

## 📂 Project Structure
Plant‑Disease‑Detection/
├── Plant_Disease_Detection_system.ipynb # Model training notebook
├── Workfiow
└── README.md # This documentation

🚀 Usage
Launch Streamlit.

Upload a clear image of a plant leaf.

View the predicted disease and confidence score.

🧠 Model Training
To train or update the model:

Open Plant_Disease_Detection.ipynb.

Load your dataset (e.g., PlantVillage).

Preprocess, build the CNN, and train the model.

Save weights as plant_disease_model.h5 for use in main_app.py.

👩‍💻 Author
Shivangi – GitHub Profile

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
