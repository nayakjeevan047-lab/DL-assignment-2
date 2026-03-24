Deep Learning Assignment 2
CNN + RNN + GAN (Applied Deep Models)
Author
Name: Jeevan Krishna
Course: Deep Learning (IS3332-1)
Institution: NMAM Institute of Technology, Nitte
Academic Year: 2025–26

Project Overview
This project focuses on implementing and evaluating three important deep learning models using PyTorch. The models are applied to different types of data including images, text, and generated content.
The project includes:
Convolutional Neural Network (CNN) for image classification
Recurrent Neural Networks (RNN, LSTM, GRU) for sentiment analysis
Generative Adversarial Network (GAN) for image generation

Objectives
To understand different deep learning architectures
To apply models on real-world datasets
To compare performance of multiple models
To analyze training behavior and results

Datasets Used
CIFAR-10
Total images: 60,000
Training: 50,000
Testing: 10,000
Classes: 10
IMDB Dataset
Total reviews: 50,000
Training: 25,000
Testing: 25,000
Classes: Positive and Negative
Fashion-MNIST
Total images: 70,000
Training: 60,000
Testing: 10,000
Image size: 28 x 28 grayscale
Classes: 10 clothing categories

Models Implemented
CNN (Image Classification)
Convolution layers with ReLU activation
Max pooling layers
Fully connected layers
Loss: Cross Entropy
RNN, LSTM, GRU (Text Classification)
Embedding layer
Recurrent layer (RNN / LSTM / GRU)
Fully connected output layer
Loss: Binary Cross Entropy
GAN (Image Generation)
Generator: Generates images from noise
Discriminator: Classifies real and fake images
Loss: Binary Cross Entropy

Tools and Technologies
Python
PyTorch
Torchvision
Torchtext
NumPy
Matplotlib
Google Colab
Training Details
CNN
Batch Size: 128
Epochs: 10 to 20
Learning Rate: 0.001
ResNet18
Batch Size: 64
Epochs: 10
Learning Rate: 0.0005
RNN / LSTM / GRU
Batch Size: 32
Epochs: 5 to 10
Learning Rate: 0.001
GAN
Batch Size: 128
Epochs: 50
Learning Rate: 0.0002
Optimizer used: Adam

Results Summary
CNN achieved good accuracy on CIFAR-10
ResNet18 performed better after fine-tuning
GRU and LSTM performed better than basic RNN
GAN successfully generated images with moderate quality
Key Learnings
Deep learning models perform differently based on data type
Hyperparameter tuning is important for better performance
Advanced models like LSTM and GRU handle sequences better
GAN training is complex and requires careful tuning
Conclusion
This project provides practical understanding of CNN, RNN-based models, and GANs. It highlights how deep learning can be applied to different problem domains such as image classification, text analysis, and data generation.

GitHub Repository
https://github.com/nayakjeevan047-lab/DL-assignment-2.git⁠�
