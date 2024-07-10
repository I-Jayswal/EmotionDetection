# Emotion Detection
This project focuses on detecting emotions from facial expressions using a Convolutional Neural Network (CNN) and Dense model.

## Dataset
The dataset used for this project contains 35,685 examples of 48x48 pixel grayscale images of faces, divided into training and testing datasets. 
The images are categorized based on the emotion shown in the facial expressions, including happiness, neutral, sadness, anger, surprise, disgust, and fear.

### Dataset Link
The dataset can be found on Kaggle: [Emotion Detection FER](https://www.kaggle.com/datasets/ananthu017/emotion-detection-fer)

## Model
We employed a Convolutional Neural Network (CNN) to extract features from the images, followed by a Dense model to classify the emotions. 
The architecture is designed to effectively handle the grayscale images and accurately predict the corresponding emotions.

## Installation
To run this project, you need to have Python installed along with the following libraries:
- TensorFlow
- Keras
- NumPy
- Matplotlib
- OpenCV (optional, for image preprocessing)
- imghdr
