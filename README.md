# 🥔 Potato Disease Classification Using CNN

## 📌 Project Overview

This project uses **Convolutional Neural Networks (CNN)** and Deep Learning to classify potato leaf images into three categories:

1. Early Blight
2. Late Blight
3. Healthy

The goal is to identify potato leaf diseases automatically using image classification.

## 🎯 Project Objectives

- Understand and implement a CNN model.
- Load and preprocess the PlantVillage dataset.
- Train a deep learning model to classify potato leaf diseases.
- Evaluate model performance.
- Save and reload the trained model.
- Test the model using sample potato leaf images.

## 📂 Dataset

**Dataset:** PlantVillage Dataset  
**Source:** Kaggle

Three potato leaf classes were selected:

| Class | Images |
|---|---:|
| Early Blight | 1,000 |
| Late Blight | 1,000 |
| Healthy | 152 |
| **Total** | **2,152** |

The dataset was divided into:
- Training: 80%
- Validation: 20%

The original dataset is not included in this repository because of its size. Download it from Kaggle to reproduce the project.

## 🧠 CNN Model Architecture

The model was built using TensorFlow and Keras.

Main layers include:

- Rescaling
- Conv2D (32 filters)
- MaxPooling2D
- Conv2D (64 filters)
- MaxPooling2D
- Conv2D (128 filters)
- MaxPooling2D
- Flatten
- Dense (128 neurons)
- Dropout (0.5)
- Dense (3 neurons, Softmax activation)

## ⚙️ Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Kaggle
- Google Drive

## 📊 Model Performance

The model was trained for 20 epochs.

**Validation Accuracy: 94.88%**

Classification report:

| Class | Precision | Recall | F1-Score |
|---|---:|---:|---:|
| Early Blight | 0.96 | 0.98 | 0.97 |
| Late Blight | 0.96 | 0.93 | 0.95 |
| Healthy | 0.84 | 0.93 | 0.88 |

## 🧪 Model Testing

The saved model was tested using three sample images from the original PlantVillage dataset:

- Early Blight → Correct Prediction
- Late Blight → Correct Prediction
- Healthy → Correct Prediction

All three sample predictions matched their expected classes.

**Note:** These three images are sample checks from the same dataset source, not an independent test set. They do not represent 100% overall model accuracy.

## 📁 Project Files

- `Potato_Disease_CNN_Image_Classification.ipynb` — Complete Google Colab notebook.
- `Potato_Disease_CNN_Model.keras` — Trained CNN model.
- `README.md` — Project documentation.

## 🚀 How to Use

1. Download or clone this repository.
2. Open the notebook in Google Colab.
3. Download the PlantVillage dataset from Kaggle.
4. Connect Google Drive.
5. Update the dataset path if needed.
6. Run the notebook cells to train or evaluate the model.

## 👨‍💻 Author

Created as a Deep Learning and Computer Vision learning project.

**Project:** Potato Disease Classification Using CNN
