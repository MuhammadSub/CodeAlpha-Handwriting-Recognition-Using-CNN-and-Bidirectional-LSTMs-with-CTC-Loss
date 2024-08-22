# Handwriting Recognition Using CNN and Bidirectional LSTMs with CTC Loss

This project demonstrates handwriting recognition using a Convolutional Neural Network (CNN) combined with Bidirectional Long Short-Term Memory (LSTM) networks and Connectionist Temporal Classification (CTC) loss. The model is designed to recognize and transcribe handwritten text from images.

## Project Overview

The model architecture includes:
- **Convolutional Layers:** Extract features from input images.
- **Bidirectional LSTM Layers:** Capture sequential dependencies in the extracted features.
- **CTC Loss:** Handle the alignment between the input image and the output text labels.

The dataset used for training and validation is sourced from Kaggle and includes images of handwritten names.

## Dataset

The dataset used in this project can be found here: [Handwriting Recognition Dataset](https://www.kaggle.com/datasets/landlord/handwriting-recognition).
