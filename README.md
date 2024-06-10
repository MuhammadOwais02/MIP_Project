# Pneumonia Detection Using Deep Learning

This repository contains the code and resources for a project aimed at detecting pneumonia from chest X-ray images using deep learning models, specifically Convolutional Neural Networks (CNNs). The project leverages several popular CNN architectures including ResNet50 and VGG16.

## Introduction
Pneumonia is a significant health issue, especially in developing countries. Early detection through chest X-rays can save lives. This project utilizes deep learning techniques to develop an automated system for pneumonia detection.

## Dataset
The dataset used for this project consists of chest X-ray images and is sourced from the following location:
- [Kaggle Dataset](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia)

## Models
The project implements multiple CNN architectures for pneumonia detection:
- **ResNet50**: Implementation can be found in `pneumonia_detection_ResNet50.ipynb`
- **VGG16**: Implementation can be found in `pneumonia_detection_vgg16_mip.ipynb`
- **Other Custom Models**: Additional models and final version implementations are provided in `PNEUMONIA_CNN.ipynb` and `PNEUMONIA_CNN_final.ipynb`

## Requirements
To run the code in this repository, ensure you have the following packages installed:
- Python 3.x
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV
- Jupyter Notebook

## Results
The results of the trained models are documented in the respective notebooks. The models achieve significant accuracy in detecting pneumonia from chest X-rays, with the detailed metrics available in the final sections of the notebooks.
