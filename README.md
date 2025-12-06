# MRI Brain Tumor Classification using VGG19 and Fine-Tuned Dense Layers

This project implements a deep learning model using a fine-tuned VGG19 architecture for the automated classification of four types of brain tumors (Glioma, Meningioma, No Tumor, and Pituitary) from MRI images.

## 🚀 Key Features

* **Transfer Learning:** Utilizes the VGG19 pre-trained Convolutional Neural Network (CNN) as a robust feature extractor.
* **Fine-Tuning:** The VGG19 base is augmented with custom, fine-tuned dense layers, Batch Normalization, and Dropout to enhance generalization and prevent overfitting.
* **Data Augmentation:** Employs Keras's `ImageDataGenerator` for robust image preprocessing and real-time data augmentation during training.
* **Comprehensive Evaluation:** Model performance is assessed using metrics like Accuracy, Loss, ROC/AUC curves, and a detailed Confusion Matrix.

## 🧠 Dataset Overview

The model is trained and evaluated on a dataset of MRI brain images categorized into four classes:
* **Glioma**
* **Meningioma**
* **No Tumor**
* **Pituitary**

| Dataset Split | Glioma | Meningioma | No Tumor | Pituitary | Total Images |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Training** | 1321 | 1339 | 1595 | 1457 | 5712 |
| **Testing** | 300 | 306 | 405 | 300 | 1311 |
| **Validation**| 175 | 139 | 162 | 179 | 655 |

*Note: The image dataset is external and not included in this repository due to size constraints. You must download and structure the data according to the paths specified in the notebook.*

## 📈 Model Performance

The model demonstrates excellent performance across all datasets, showcasing high accuracy and minimal loss.

* **Test Accuracy:** Approximately **99.3%**
* **Key Techniques:** The addition of dense layers, batch normalization, and dropout mechanisms enhanced the model's ability to generalize.

## ⚙️ Installation and Setup

### 1. Clone the Repository
```bash
git clone <https://github.com/shreyanshmishra8899-lab/Brain-Tumor-Detection-using-VGG19-with-Fine-Tuning>
cd mri-brain-tumor-vgg19
