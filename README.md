# Face Mask Detection Using CNN

## Learning Objectives

At the end of the experiment, you will be able to:

- Load and extract features of images using ImageDataGenerator
- Build convolutional neural networks
- Use pre-trained models using Keras applications

## Introduction

This project utilizes a Deep Neural Network, specifically a Convolutional Neural Network (CNN), to differentiate between images of people with masks, without masks, and incorrectly placed masks. Both manually built and pre-trained networks are employed to perform this classification task.

### Purpose

The outbreak of the Coronavirus pandemic has necessitated wearing masks in public spaces. This project addresses the challenge of detecting people not wearing masks correctly. By utilizing image processing and deep learning techniques, the project aims to classify faces into three classes: with masks, without masks, and partially masked. The application of this project extends to various environments such as schools, hospitals, banks, and airports, serving as a digital scanning tool for mask compliance.

## Dataset

The dataset consists of 5029 training images and 1059 test images, categorized into three classes: with_mask, without_mask, and partial_mask. Images were sourced from various internet platforms and include general frontal face images considered as without mask. Some images contain artificially generated masks to augment the 'masked' data category.

## Implementation

The project involves several key steps:

1. Data preprocessing using ImageDataGenerator to load and augment image data.
2. Building CNN models from scratch with custom architectures.
3. Utilizing pre-trained models like VGG16 and ResNet50 for transfer learning.
4. Evaluating model performance using metrics such as accuracy, loss, and validation accuracy.
5. Live image prediction using captured photos for real-time mask detection.

## Report Analysis

* Model Performance: Model 2, with additional convolutional layers, outperformed Model 1, indicating the importance of deeper architectures for better feature extraction.

    1. The project utilized various CNN architectures and pre-trained models such as VGG16 and ResNet50 to classify images into three categories: with mask, without mask, and partial mask.
    2. Overall, the models achieved promising results with accuracies ranging from 90% to 96%.

* Real-time Prediction: The live image capture feature successfully predicted whether individuals were wearing masks, providing instant feedback for safety compliance.

## Future Scope

- Interactive Interface: Develop a user-friendly interface for easy deployment and usage in different settings.
- Integration with Surveillance Systems: Integrate the model with existing surveillance systems for automated monitoring and alerting.
