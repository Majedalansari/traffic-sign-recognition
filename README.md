# Traffic Sign Recognition Using CNN

This project uses a Convolutional Neural Network (CNN) to classify traffic signs from the GTSRB dataset.

## Project Overview

The dataset contains 43 different traffic sign classes. Images were resized to 30x30 pixels and normalized before training.

A CNN model was built using TensorFlow and Keras to recognize and classify the traffic signs.

## Model Performance

- Test Accuracy: 97.39%
- Test Loss: 0.1132
- Number of Classes: 43
- Number of Images: 26,640

## Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn

## Model Architecture

- Convolutional Layer
- Max Pooling Layer
- Convolutional Layer
- Max Pooling Layer
- Flatten Layer
- Dense Layer
- Softmax Output Layer

## Project Steps

1. Download and extract the GTSRB dataset
2. Load and preprocess the images
3. Split the dataset into training and testing sets
4. Normalize the images
5. Build the CNN model
6. Train the model
7. Evaluate the model
8. Test predictions
9. Save the trained model

## Result

The CNN achieved approximately 97.4% test accuracy on the GTSRB traffic sign dataset.
