![download (5)](https://github.com/user-attachments/assets/bbfbdb6b-6156-44ed-8820-c03f6c884cbe)

# Project Description
This project aims to detect and classify Alzheimer's disease using MRI brain images. The OASIS dataset has been utilized, and deep learning models are implemented using PyTorch.
Alzheimer's disease is a progressive neurodegenerative disorder that develops in multiple stages:
Early Stage: Mild memory loss and minor cognitive issues.
Middle Stage: More noticeable problems in learning, problem-solving, and communication.
Advanced Stage: Severe cognitive decline and inability to perform daily tasks.
The goal of this project is to classify MRI images into different stages of Alzheimer's to enable early and precise diagnosis.


# Dataset (OASIS)
The OASIS (Open Access Series of Imaging Studies) dataset contains MRI scans of both Alzheimer's patients and healthy individuals. The dataset includes detailed information about disease progression and demographic data, which enhance model accuracy.
https://www.kaggle.com/datasets/ninadaithal/imagesoasis?select=Data


# Final Model: MobileNetV3
We utilized MobileNetV3, a lightweight and efficient neural network for image processing, optimized for low-power devices while maintaining high classification accuracy.
MobileNetV3 Features:
Depthwise Separable Convolution reduces computational complexity.
h-swish activation function improves network efficiency.
Squeeze-and-Excitation (SE) Blocks enhance feature extraction.
Lower memory consumption and processing power compared to heavier models like ResNet.

![Modified-MobileNetV3-architecture](https://github.com/user-attachments/assets/253e4b53-321c-4794-b9d6-2566fe3eaf61)

# Architecture and Implementation
MRI images are preprocessed and resized to the required dimensions.
Data Augmentation (rotation, brightness adjustment, rescaling) is applied for robustness.
The dataset is split into Training and Testing sets.
Transfer Learning is employed for faster and more efficient training.
AdamW Optimizer and Cross-Entropy Loss are used for model optimization.

# Results and Findings
The MobileNetV3 model has been implemented to distinguish Alzheimer's patients from healthy people. Analysis of the results shows that this model has less processing time and acceptable accuracy compared to heavier models such as ResNet. This feature makes this model usable in real-time and low-cost medical diagnosis systems.

![download (2)](https://github.com/user-attachments/assets/2064868d-3bb6-4aee-9b1a-5c2bdf249257)


