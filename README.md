# Variational Autoencoder (VAE) for Image Generation

This project implements a Variational Autoencoder (VAE) using TensorFlow/Keras for generating images based on the MNIST dataset. The VAE is a type of generative model that learns to represent high-dimensional data in a lower-dimensional latent space and generate new samples from this space.

### Features:

- **Encoder-Decoder Architecture:** Utilizes a neural network-based encoder to map input images into a latent space and a decoder to reconstruct images from sampled latent vectors.
  
- **Loss Function:** Includes a combination of reconstruction loss (e.g., binary cross-entropy) and Kullback-Leibler (KL) divergence to regularize the latent space.

- **Training and Inference:** Trains the VAE on MNIST digits dataset, optimizing the model to generate realistic digit images. Provides functionality to sample from the learned latent space to generate new digit images.

