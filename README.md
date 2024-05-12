## American Sign Language Detection

# Abstract
This project focuses on detecting five vowels (A, E, I, O, U) in sign language using convolutional neural networks (CNNs). Various data augmentation techniques were employed to enhance the dataset. Five different architectures were tested, including VGG-16, GoogleNet, ResNet, NIN, and a simple CNN model. Results showed that simpler models like GoogleNet and the simple CNN exhibited more robust results in terms of efficiency and compatibility, despite the higher accuracy of more complex architectures like ResNet.

# Dataset
Link: https://drive.google.com/drive/folders/1mVkEIHwskNKGcJeyzBvZZtbbS51I-V3m?usp=drive_link

# Introduction
Sign language, a crucial form of communication for the deaf community, faces challenges in accurate recognition. This study focuses on detecting five vowels (A, E, I, O, U) in sign language using CNNs.

# Problem Statement
Developing effective tools for sign language recognition remains challenging. This study aims to detect five distinct alphabets within sign language to improve recognition for individuals with hearing impairments.

# Methodology
Setup: Initial coding phase in Google Colab, transitioned to Jupyter Notebook for better data management. Images captured using a standard iPhone camera.
Dataset: Images of vowels captured from 20 angles against a clean white background. Data augmentation techniques applied to expand the dataset size. Dataset divided into training (80%) and testing (20%) sets.
CNN Architecture: Tested architectures include VGG-16, GoogleNet, ResNet, NIN, and a simple CNN model. GoogleNet and the simple CNN showed better efficiency and compatibility.

## Challenges**
Unequal class distribution.
Grayscale images compatibility.
Long training times for extensive architectures like ResNet and NIN.
Results and Discussion
Simple CNN model achieved an accuracy of 85%.
GoogleNet showed an accuracy of 90.38% with a training time of 4.28 minutes.
ResNet achieved 84% accuracy with a training time of 10.72 minutes.
VGG-16 exhibited an accuracy of 25% with a training time of 120 minutes.
NIN showed an accuracy of 20%.

## Conclusion
Simpler models like GoogleNet and the simple CNN showed better efficiency and compatibility than more complex architectures like ResNet, despite their lower accuracy. Future research could focus on expanding the dataset to include more sign language symbols and languages.

