# Emotion Detection Project

## Overview
This project enhances Facial Emotion Recognition (FER) by integrating Residual Networks (ResNet) with Squeeze-and-Excitation (SE) blocks and a bagging ensemble approach. The ensemble is trained on FER2013 dataset publicly available on kaggle and detect seven different emotions from grayscale images with dimensions 227x227 pixels. The emotions include happiness, sadness, anger, surprise, fear, disgust, and neutral.

## Required tools
- Python 3.x
- PyTorch
- matplotlib
- NumPy
- torchensemble

## Usage
1. Clone this repository:
    ```
    git clone https://github.com/your_username/Emotion_detection.git
    ```

2. Navigate to the project directory:
    ```
    cd Emotion_detection
    ```

3. Ensure that all required libraries are installed(if not already):
    ```
    pip install -r requirements.txt
    ```

4. Prepare your dataset:
    - Organize your grayscale images into folders corresponding to each emotion.
    - Ensure that each image has dimensions of 227x227 pixels.

5. Training and testing the model:
    - ipynb file contains code for both training and testing the model.
    - Pretrained ensemble is provided in a zip file.
