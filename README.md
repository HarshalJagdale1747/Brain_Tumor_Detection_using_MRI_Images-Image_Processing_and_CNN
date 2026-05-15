# Brain Tumor Detection using MRI Images, Image Processing and CNN

## Overview

This repository contains two practical implementations related to Brain Tumor Detection using MRI images.

The project combines:
1. Digital Image Processing Techniques
2. Deep Learning using CNN

The system preprocesses MRI images, performs segmentation and feature extraction, and classifies tumor types automatically.

---

# Repository Structure

```text
├── Brain_Tumor_Detection_DSIP_Practical_1.ipynb
├── Brain_Tumor_Detection_DSIP_Practical_2.ipynb
├── images/
├── README.md
```

---

# Technique  1 — Brain Tumor Detection using Image Processing

## Objective

To understand and implement basic Digital Image Processing techniques for MRI brain tumor analysis.

---

# Techniques Used

## Image Preprocessing
- Resize Image
- Grayscale Conversion
- Histogram Equalization
- CLAHE Enhancement

---

## Image Segmentation
- Binary Thresholding
- Region Growing

---

## Edge Detection
- Canny Edge Detection
- Sobel Edge Detection

---

## Morphological Operations
- Erosion
- Dilation
- Opening
- Closing

---

## Feature Extraction
- Contours
- Boundary Descriptors
- Region Descriptors
- Bounding Box Detection

---

# Workflow

```text
MRI Image
    ↓
Preprocessing
    ↓
Grayscale Conversion
    ↓
Thresholding
    ↓
Edge Detection
    ↓
Region Growing
    ↓
Morphological Operations
    ↓
Feature Extraction
    ↓
Tumor Visualization
```

---

# Sample Outputs

---

## Original image and different image processing operation with Histogram Graph 

![Edge](Output Images/download.png)

---

## Train Vs Validation 

![Edge](Output%20Images/download.png)


---

## Confusion Matrix 

![Binary](Output Images/download (2).png)

---

## HEatmap 

![Edge](Output Images/download (3).png)

---

## Original MRI VS Output image 

![Region](Output Images/download (4).png)

--

# Applications

- Medical Image Segmentation
- MRI Enhancement
- Tumor Region Analysis
- Medical Research

---

# Notebook

Run:

```bash
Brain_Tumor_Detection_DSIP_Practical_1.ipynb
```

---

# Technique  2 — Brain Tumor Detection using CNN and Deep Learning

## Objective

To design and implement an AI-based Brain Tumor Detection System using MRI images and Convolutional Neural Networks (CNN).

---

# Features

- CNN based Tumor Classification
- MRI Image Enhancement
- Noise Removal
- Segmentation
- Tumor Detection
- Automatic Classification
- Result Visualization

---

# Tumor Classes

The CNN model classifies MRI images into:

1. Glioma
2. Meningioma
3. Pituitary
4. No Tumor

---

# Deep Learning Workflow

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
Prediction Visualization
```

---

# CNN Architecture

- Convolution Layer
- ReLU Activation
- Max Pooling
- Flatten Layer
- Dense Layer
- Softmax Layer

---

# Training Details

| Parameter | Value |
|---|---|
| Epochs | 10 |
| Batch Size | 32 |
| Optimizer | Adam |
| Loss Function | Categorical Crossentropy |
| Image Size | 128 × 128 |

---

# Dataset Information

Dataset Used:

Brain Tumor MRI Dataset

Dataset Link:

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

---

# Dataset Split

| Dataset | Percentage |
|---|---|
| Training | 68% |
| Validation | 12% |
| Testing | 20% |

---

# Performance

| Metric | Result |
|---|---|
| Accuracy | 85% |
| Precision | High |
| Recall | High |
| F1-Score | Good |

---

# Output Features

- Tumor Bounding Box
- Tumor Contours
- Predicted Tumor Class
- Confidence Score
- Segmented Tumor Region

---

# Sample Results

## Original MRI and Grayscale image of original MRI image of glioma, meningioma, notumor, pituitary 

![Preprocessing](Output Images/download (5).png)

---

## Image Restoration 

![Segmentation](Output Images/download (6).png)

---

## Binary Conversation

![Accuracy](Output Images/download (7).png)

---

## Edge Detection 

![Confusion](Output Images/download (8).png)

---

## Region growing and watershed

![Prediction](Output Images/download (9).png)

---

---

## Morphological operation 

![Prediction](Output Images/download (10).png)

---

---

## Feature extraction 

![Prediction](Output Images/download (11).png)

---

---

## Dataset distribution 

![Prediction](Output Images/download (12).png)

---

---

## Accuracy and Loss

![Prediction](Output Images/download (13).png)

---

---

## Confusion matrix 

![Prediction](Output Images/download (14).png)

---

---

## Accurately predicted PITUITARY

![Prediction](Output Images/download (15).png)

---

---

## Accurately predicted GLIOMA 

![Prediction](Output Images/download (16).png)

---

# Applications

- Hospital Radiology Assistance
- Early Tumor Screening
- Telemedicine
- Medical AI Systems
- Healthcare Diagnosis Support

---

# Advantages

- Automatic Tumor Detection
- Reduced Manual Effort
- High Accuracy
- Fast Diagnosis
- Improved MRI Visualization

---

# Future Scope

- Real-Time Detection
- Cloud-Based MRI Analysis
- 3D MRI Tumor Detection
- Advanced CNN Models
- Integration with Hospital Systems

---

# Research Paper References

## Pereira et al. (2016)

CNN-based Brain Tumor Segmentation

https://ieeexplore.ieee.org/document/7780913

---

## Havaei et al. (2017)

Brain Tumor Detection using Deep Neural Networks

https://arxiv.org/abs/1505.03540

---

## Abiwinanda et al. (2019)

CNN based Brain Tumor Classification

https://iopscience.iop.org/article/10.1088/1742-6596/1192/1/012002/pdf

---

# Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- Scikit-image
- Google Colab

---

# Installation

## Install Dependencies

```bash
pip install tensorflow opencv-python matplotlib seaborn scikit-learn scikit-image
```

---

# Run the Project

## Part 1

```bash
Brain_Tumor_Detection_DSIP_Practical_1.ipynb
```

## Part 2

```bash
Brain_Tumor_Detection_DSIP_Practical_2.ipynb
```

Run all cells in Google Colab or Jupyter Notebook.

---

# Author

Harshal Jagdale

Electronics & Telecommunication Engineering

---

# License

This project is developed for educational and research purposes.
