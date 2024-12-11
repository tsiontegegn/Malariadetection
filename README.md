# Malariadetection
This project uses a deep learning model to classify malaria cell images as either parasitized or uninfected.

Image Preprocessing:
The images are resized to 128x128 pixels, converted to grayscale, and binarized using Otsu’s thresholding to simplify the classification task. Labels are assigned (1 for parasitized, 0 for uninfected), and the dataset is split into training (80%), validation (10%), and test (10%) sets.

Model Architecture:
The model is a Convolutional Neural Network (CNN) designed for binary classification. It consists of three convolutional blocks for feature extraction and a fully connected classifier. Batch normalization, ReLU activations, and dropout are incorporated for stable training and overfitting prevention. The final layer outputs probabilities for the two classes.
