# Signature Generation with VAE and GAN

This repository contains the implementation, training, and evaluation of a **Variational Autoencoder (VAE)** and a **Generative Adversarial Network (GAN)** for signature generation tasks. The project explores the ability of these models to learn and generate realistic signatures.


## Introduction
The project focuses on training **VAE** and **GAN** models to generate and reconstruct handwritten signatures. Both models were trained on a signature dataset, and their performance was assessed using loss metrics and qualitative visualization of generated signatures.

## Dataset
The project uses a signature dataset containing images of handwritten signatures. The dataset is preprocessed to normalize the images for model training.

## Model Architectures
### Variational Autoencoder (VAE)
- Encoder: Encodes the input signature into a latent representation.
- Decoder: Reconstructs the signature from the latent representation.

### Generative Adversarial Network (GAN)
- Generator: Produces synthetic signatures.
- Discriminator: Distinguishes between real and generated signatures.

## Training Details
- **VAE**:
  - Monitored using reconstruction loss.
  - Achieved a final test reconstruction loss of **7350.74**.
- **GAN**:
  - Monitored using discriminator and generator losses.
  - Trained over **130 epochs** with fluctuating loss metrics.

## Results
- **Generated Signatures**: Synthetic signatures generated by the GAN.
- **Reconstructed Signatures**: Signatures reconstructed by the VAE.
- **Challenges**: Fluctuations in GAN losses and high reconstruction loss for VAE indicate challenges in model optimization.


