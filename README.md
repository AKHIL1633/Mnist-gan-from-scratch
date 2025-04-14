# Mnist-gan-from-scratch

# Project Overview

This project implements a Generative Adversarial Network (GAN) from scratch using the MNIST dataset. The goal is to train a generator to create realistic handwritten digits and a discriminator to distinguish between real and fake images. This project is ideal for learning the inner workings of GANs and experimenting with basic deep learning architectures.

# Features 
- Build and train a GAN using TensorFlow and Keras.
-Load and preprocess the MNIST dataset (grayscale 28x28 handwritten digits).

# Design and implement:

- A Generator to create digit images from random noise.

- A Discriminator to classify images as real or fake.

- Visualize training progress with sample image generation.

- Custom training loop with manual control over loss functions and optimizers.

# Methodology

- Preprocessing: Normalize MNIST images to [-1, 1] range to stabilize GAN training.

- Model Architecture:

    - Generator:

Dense projection layer followed by reshaping to image form.

Upsampling using Conv2DTranspose layers with LeakyReLU and BatchNormalization.

Discriminator:

CNN-based model with Conv2D layers, dropout, and dense output for binary classification.




