# Image Classification using CNN model and ResNet moel 

## Introduction 
#### This project aims to build and train deep learning models to classify cat pictures from dog pictures, using accuracy and f1 score as evaluation matrices. We start with resizing and converting the pictures to grayscale. After preprocessing the pictures, we train a 4_convolution CNN model, and 6_convolution CNN model with 30 epoches. Due to the low accuracy of the previous models, we also preprocess the data using ImageGenerator from keras, where we spot a large improvement in accuracy. With the same preprocessing method, we also train a ResNet 50 model. 

## Source
### The data is obtained from Kaggle (https://www.kaggle.com/c/dogs-vs-cats.) There was 25000 pictures provided in the train data. For the purpose of our project, we will only be uing a 2000 pictures to train our model (1000 dog & 1000 cat.)
