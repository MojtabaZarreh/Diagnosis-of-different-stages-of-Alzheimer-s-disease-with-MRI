# Alzheimer Detection with Deep Learning

# Project Description
This project aims to detect and classify Alzheimer's disease using MRI brain images. The OASIS dataset has been utilized, and deep learning models are implemented using PyTorch.
Alzheimer's disease is a progressive neurodegenerative disorder that develops in multiple stages:
Early Stage: Mild memory loss and minor cognitive issues.
Middle Stage: More noticeable problems in learning, problem-solving, and communication.
Advanced Stage: Severe cognitive decline and inability to perform daily tasks.
The goal of this project is to classify MRI images into different stages of Alzheimer's to enable early and precise diagnosis.


# Dataset (OASIS)
The OASIS (Open Access Series of Imaging Studies) dataset contains MRI scans of both Alzheimer's patients and healthy individuals. The dataset includes detailed information about disease progression and demographic data, which enhance model accuracy.


# Final Model: MobileNetV3
We utilized MobileNetV3, a lightweight and efficient neural network for image processing, optimized for low-power devices while maintaining high classification accuracy.
MobileNetV3 Features:
Depthwise Separable Convolution reduces computational complexity.
h-swish activation function improves network efficiency.
Squeeze-and-Excitation (SE) Blocks enhance feature extraction.
Lower memory consumption and processing power compared to heavier models like ResNet.
![Modified-MobileNetV3-architecture](https://github.com/user-attachments/assets/253e4b53-321c-4794-b9d6-2566fe3eaf61)
