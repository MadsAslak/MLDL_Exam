# MLDL_Exam
Machine-Learning and Deep-Learning Exam Folder

Melanoma Detection Using Neural Networks

Project Overview

This repository contains the research and implementation of a machine learning model using neural networks to distinguish between benign and malignant melanoma from dermatological images. The aim of this project is to improve early diagnosis and contribute to the ongoing efforts in medical image analysis using artificial intelligence.

Motivation

Melanoma, a type of skin cancer originating from melanocytes, has a high cure rate if detected early. However, distinguishing between benign and malignant melanoma visually can be challenging. This project explores the capability of neural networks to automate and enhance the accuracy of such classifications, potentially aiding dermatologists in early and more reliable diagnosis.

Dataset

The dataset comprises 14,000 images, evenly split between benign and malignant cases, annotated and collected under controlled conditions. Due to privacy concerns and the terms of use, the dataset is not publicly available in this repository.

Data Characteristics: Image Count: 14,000 Categories: Benign and Malignant Annotations: Includes markings such as circles or arrows indicating areas of interest. Diversity: Currently limited to images of white skin; future work will aim to include a more diverse set of skin tones. Methodology

Preprocessing Normalization: Scale and normalize image sizes and pixel values. Augmentation: Apply data augmentation techniques to increase model robustness. Cleaning: Address and remove any potential biases introduced by annotations and image quality variations. Model Architecture We use Convolutional Neural Networks (CNNs), specifically exploring architectures like ResNet and Inception for their ability to handle image data effectively. Evaluation Models are evaluated based on their sensitivity and specificity, with a focus on minimizing false negatives due to the severe implications of missing a malignant diagnosis. Results

Note: The results will be continuously updated as the models are trained and evaluated.

Initial Testing: Preliminary results show promising accuracy levels above 90%. Detailed performance metrics and comparisons will be provided. Usage
