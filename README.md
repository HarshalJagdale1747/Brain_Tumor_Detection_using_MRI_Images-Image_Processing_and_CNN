# Brain Tumor Detection using MRI Images and Basic Image Processing

## Overview

This project focuses on Brain Tumor Detection using Digital Image Processing techniques on MRI images. The system performs preprocessing, segmentation, edge detection, region growing, morphological operations, and feature extraction for identifying tumor regions.

The project demonstrates how classical image processing methods can help analyze medical MRI images before applying Deep Learning models.

---

# Features

- MRI Image Preprocessing
- Grayscale Conversion
- Binary Thresholding
- Edge Detection using Canny
- Region Growing Segmentation
- Morphological Operations
- Feature Extraction
- Histogram Analysis
- Tumor Visualization

---

# Technologies Used

- Python
- OpenCV
- NumPy
- Matplotlib
- Scikit-image
- Google Colab

---

# Dataset

Dataset Used:

Brain Tumor MRI Dataset

Dataset Link:

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

---

# Image Processing Techniques Used

## 1. Grayscale Conversion
Converts MRI image into grayscale for easier processing.

## 2. Binary Thresholding
Separates tumor region from background.

## 3. Edge Detection
Canny edge detection used for tumor boundary extraction.

## 4. Region Growing
Groups neighboring pixels having similar intensity values.

## 5. Morphological Operations
- Erosion
- Dilation
- Opening
- Closing

## 6. Feature Extraction
Extracts:
- Area
- Perimeter
- Contours
- Bounding Box

---

# Project Workflow

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

## Original MRI Image

![Original](images/original.png)

---

## Binary Conversion

![Binary](images/binary.png)

---

## Edge Detection

![Edge](images/edge.png)

---

## Region Growing

![Region](images/region.png)

---

## Morphological Operations

![Morphology](images/morphology.png)

---

# Applications

- Brain Tumor Analysis
- Medical Image Segmentation
- MRI Enhancement
- Healthcare Assistance
- Medical Research

---

# How to Run

## Install Libraries

```bash
pip install opencv-python numpy matplotlib scikit-image tensorflow
```

## Run Notebook

Open Jupyter Notebook or Google Colab and run:

```bash
Brain_Tumor_Detection_DSIP_Practical_1.ipynb
```

---

# Author

Harshal Jagdale

Electronics & Telecommunication Engineering

---
