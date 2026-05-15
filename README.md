# Brain Tumor Detection using MRI Images, Image Processing and CNN

## Overview

This project presents an automated Brain Tumor Detection System using MRI images, Digital Image Processing techniques, and Convolutional Neural Networks (CNN). The system preprocesses MRI images, performs segmentation and feature extraction, and classifies tumor types using Deep Learning.

The project aims to assist healthcare professionals in early brain tumor diagnosis and reduce manual analysis effort.

---

# Features

- MRI Image based Brain Tumor Detection
- Image Preprocessing and Enhancement
- Grayscale Conversion
- Histogram Equalization and CLAHE
- Gaussian and Median Filtering
- Binary Thresholding
- Edge Detection using Canny Algorithm
- Region Growing Segmentation
- Morphological Operations (Erosion & Dilation)
- Feature Extraction using Contours and Region Descriptors
- CNN based Tumor Classification
- Tumor Visualization using Bounding Boxes and Contours
- Accuracy, Precision, Recall, F1-score Analysis
- Confusion Matrix and Heatmap Visualization

---

# Tumor Classes

The CNN model classifies MRI images into the following categories:

1. Glioma
2. Meningioma
3. Pituitary
4. No Tumor

---

# Dataset

Dataset Used:

Brain Tumor MRI Dataset from Kaggle

Dataset Link:

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

---

# Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

---

# Methodology

## 1. Image Acquisition
MRI brain images are collected from the dataset.

## 2. Image Preprocessing
- Resize images
- Convert to grayscale
- Histogram equalization
- CLAHE enhancement

## 3. Noise Removal
- Gaussian filtering
- Median filtering

## 4. Segmentation
- Binary Thresholding
- Region Growing
- Edge Detection

## 5. Morphological Operations
- Erosion
- Dilation
- Opening
- Closing

## 6. Feature Extraction
- Contour detection
- Boundary descriptors
- Region descriptors

## 7. CNN Classification
Convolutional Neural Network is trained to classify tumor types.

## 8. Result Visualization
The final output displays:
- Tumor class
- Confidence score
- Tumor contour
- Bounding box

---

# CNN Training Details

| Parameter | Value |
|---|---|
| Epochs | 10 |
| Batch Size | 32 |
| Optimizer | Adam |
| Loss Function | Categorical Crossentropy |
| Image Size | 128 × 128 |

---

# Dataset Split

| Dataset | Percentage |
|---|---|
| Training | 68% |
| Validation | 12% |
| Testing | 20% |

---

# Performance

- Test Accuracy: ~85%
- High Precision and Recall across all tumor classes
- Efficient MRI preprocessing and segmentation

---

# Project Workflow

```text
MRI Dataset
     ↓
Preprocessing
     ↓
Filtering & Enhancement
     ↓
Segmentation
     ↓
Morphological Operations
     ↓
Feature Extraction
     ↓
CNN Training
     ↓
Tumor Classification
     ↓
Result Visualization
```

---

# Applications

- Hospital Radiology Assistance
- Early Brain Tumor Screening
- Telemedicine Diagnosis Support
- Medical Image Analysis
- Healthcare AI Systems

---

# Advantages

- Automatic Brain Tumor Detection
- Reduced Manual Effort
- Faster Diagnosis
- Improved MRI Image Quality
- Accurate Classification using CNN
- Tumor Boundary Visualization

---

# Future Scope

- Real-time MRI Analysis
- Integration with Hospital Systems
- 3D MRI Brain Tumor Detection
- Cloud-based Medical Diagnosis
- Advanced Deep Learning Models (ResNet, U-Net)

---

# Research Papers Reference

## 1. Pereira et al. (2016)
CNN-based Brain Tumor Segmentation

https://ieeexplore.ieee.org/document/7780913

## 2. Havaei et al. (2017)
Brain Tumor Detection using Deep Neural Networks

https://arxiv.org/abs/1505.03540

## 3. Mohsen et al. (2018)
Deep Learning with MRI Classification

https://www.sciencedirect.com/science/article/pii/S0933365718305284

## 4. Abiwinanda et al. (2019)
CNN based Brain Tumor Classification

https://iopscience.iop.org/article/10.1088/1742-6596/1192/1/012002/pdf

---

# How to Run the Project

## Clone Repository

```bash
git clone https://github.com/your-username/brain-tumor-detection.git
```

## Install Dependencies

```bash
pip install tensorflow opencv-python matplotlib numpy scikit-learn
```

## Run Jupyter Notebook

```bash
jupyter notebook
```

Open the `.ipynb` notebook and run all cells.

---

# Output Example

The output displays:
- Original MRI Image
- Segmented Tumor Region
- Tumor Contours
- Bounding Box
- Predicted Tumor Type
- Confidence Score

---

# Author

Harshal Jagdale

Electronics & Telecommunication Engineering

Brain Tumor Detection using MRI Images and CNN

---

# License

This project is developed for educational and research purposes.
