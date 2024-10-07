# Keyword-Spotting
Final project of the course Human Data Analytics in the Physics of Data master degree at University of Padova.

## Description
Nowadays, keyword spotting is a crucial step that must be taking in order to advance to the next era for communication between humans an devices. Many methods for training algorithms exist but the most relevant are related with machine learning, specially with Neural Networks. In this work we tested a generic Convolutional Neural Network (CNN) with a dataset made of 30 labels. It was found that the Short Time Fourier Transform (STFT) feature extractor is the best in terms of efficiency and accuracy but can be still improved. A second model architecture based on Recurrent Neural Networks (RNNs) was tested and for avoiding overfitting, regularization methods were implemented. Finally, it was found that the most efficient and low complexity model is STFT with a l2 regularization of 0.01 and 0.3 dropout value.

## Language
Python (TensorFlow)
