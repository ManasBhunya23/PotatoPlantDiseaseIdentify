# Potato Plant Disease Stage Identification using CNN

This project aims to identify the stage of disease in potato plants by analyzing images of their leaves. The project uses a Convolutional Neural Network (CNN) to classify the disease stages based on visual symptoms present on the leaves.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Potato plants are susceptible to various diseases that can significantly affect crop yield. Early detection and accurate identification of the disease stage are crucial for effective treatment. This project leverages deep learning techniques to classify images of potato leaves into different stages of disease, helping farmers and agronomists make informed decisions.

## Features
- **Automated Disease Stage Detection:** Classifies the disease stage based on leaf images.
- **CNN Model:** Utilizes a Convolutional Neural Network for image classification.
- **Real-time Predictions:** Capable of providing real-time disease stage identification.
- **Scalable:** Easily extendable to other plant diseases or stages.

## Dataset
The dataset used for training and testing the CNN model consists of images of potato leaves labeled with different disease stages. The dataset is sourced from [Kaggle](https://www.kaggle.com/datasets) and includes:

- Healthy leaves
- Early-stage disease leaves
- Mid-stage disease leaves
- Late-stage disease leaves

## Model Architecture
The CNN model is designed with the following architecture:

- **Input Layer:** Image of a potato leaf (typically resized to 128x128 pixels).
- **Convolutional Layers:** Multiple layers with ReLU activation for feature extraction.
- **Pooling Layers:** Max-pooling layers to reduce dimensionality.
- **Fully Connected Layers:** Dense layers to classify the extracted features.
- **Output Layer:** Softmax activation for multi-class classification into disease stages.

