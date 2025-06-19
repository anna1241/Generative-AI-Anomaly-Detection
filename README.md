# Generative AI Anomaly Detection

This project implements and compares various Generative AI-based anomaly detection techniques on image datasets (MNIST Digits and MNIST Fashion). The project focuses on using deep learning models such as Generative Adversarial Networks (GANs) and Variational Autoencoders (VAEs) to generate, reconstruct, and identify anomalies effectively.

## Objectives

- Explore MNIST Digits and MNIST Fashion datasets through Exploratory Data Analysis (EDA)
- Build and train GAN models for anomaly detection in handwritten digits and fashion images
- Build and train VAE models for anomaly detection and latent space exploration
- Compare GAN and VAE on image quality, training stability, and latent space learning
- Apply VAE for anomaly detection in a real-world domain to drive financial savings

## Datasets

- **MNIST Digits:** 28×28 grayscale images of handwritten digits (0-9)
- **MNIST Fashion:** 28×28 grayscale images of clothing items (10 classes)


## Models

### Generative Adversarial Network (GAN)
- **Generator:** Neural net generating fake images from noise
- **Discriminator:** Neural net distinguishing real from fake images
- **Training:** Min-max adversarial game with binary cross-entropy loss

### Variational Autoencoder (VAE)
- **Encoder:** Compresses image to latent vector (mu, logvar)
- **Reparameterization:** Enables gradient-based sampling
- **Decoder:** Reconstructs image from latent vector
- **Loss:** BCE + KL Divergence

## Results

✅ Generated images from GANs and VAEs on both datasets  
✅ Latent space visualizations (PCA/t-SNE)  
✅ Comparative analysis of model performance  
✅ VAE-based anomaly detection applied to a selected real-world domain

## Key Features

- GAN and VAE architectures implemented with PyTorch
- Comparison of generated image quality and latent space representations
- Open-ended anomaly detection task addressing financial loss prevention

