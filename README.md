# ASL Alphabet Recognition Model

## Overview
This project uses a Convolutional Neural Network (CNN) to recognize American Sign Language (ASL) gestures for the alphabet, along with specific symbols for "space," "nothing," and "delete." The model achieves 99.78% accuracy on the test set, making it highly effective for ASL gesture recognition tasks.

## Dataset Preparation
1. **Data Source**: Images organized into directories named after gesture classes.

2. **Image Resizing**: All images resized to 150x150.

3. **Label Encoding**: Numeric labels mapped to gesture classes (0-28).

4. **Visualization**: Random samples displayed to verify the dataset.

**Dataset Link**: ((https://www.kaggle.com/datasets/grassknoted/asl-alphabet)

**My Kaggle Code**: (https://www.kaggle.com/code/fatmaabdulfattah/sign-language-recognition-using-cnn)

## Model & Training
1. CNN with 3 convolutional layers, batch normalization, dropout, and dense layers for classification.

2. Training metrics include ~95% training accuracy and 99.78% test accuracy after 10 epochs.

3. Optimizer: Adam; Loss: Sparse Categorical Crossentropy.

4. Early stopping and learning rate scheduling applied.

**Evaluation**: Near-perfect precision, recall, and F1-scores demonstrated via a confusion matrix and classification report.



## How to Use

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/fatmaabdulfattah/Sign-Language-Recognition-using-CNN.git
    ```


2. **Install Required Packages:**

    ```bash
    pip install -r requirements.txt
    ```




