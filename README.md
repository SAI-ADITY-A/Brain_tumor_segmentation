# Brain Tumor Segmentation Using U-Net and OpenCV

## Project Overview
This project implements a brain tumor segmentation system using the U-Net architecture and OpenCV. The goal is to segment brain tumors from MRI images accurately. U-Net is a powerful neural network designed for biomedical image segmentation, and OpenCV is used for image processing tasks such as augmentation and visualization.

## Features
- Data pre-processing using OpenCV
- Tumor segmentation using U-Net architecture
- Data augmentation for better generalization
- Evaluation of the segmentation results with dice coefficient and IOU (Intersection over Union)

## Dataset
The dataset consists of MRI images of brain scans. Each image has a corresponding mask where the tumor region is annotated. The dataset can be downloaded from [Kaggle](https://www.kaggle.com/datasets) or similar medical imaging datasets.

## Requirements
To install all dependencies, run:
```bash
pip install -r requirements.txt
