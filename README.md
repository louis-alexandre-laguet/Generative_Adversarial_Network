# Implementation of GANs and Variants on Different Datasets

This repository contains several implementations of Generative Adversarial Networks (GANs) and their variants. The objective of these exercises is to explore GANs for image generation, starting from a simple DCGAN to a conditional version with WGAN-GP.

## Repository Content

### 1. DCGAN on Lego Brick Images
**Objective:**
- Train a DCGAN (Deep Convolutional GAN) to generate grayscale 64x64 pixel images of Lego bricks.
- Use convolutional discriminator and generator.
- Visualize the evolution of generated images throughout the training process.

### 2. WGAN-GP (Wasserstein GAN with Gradient Penalty)
**Objective:**
- Understand the limitations of standard GANs (instability, mode collapse) and see how WGAN addresses them.
- Implement a WGAN using the Wasserstein distance instead of the Jensen-Shannon divergence.
- Apply the Gradient Penalty (GP) to stabilize the training by forcing the critic to satisfy the Lipschitz condition.
- Compare performance with a standard GAN.

### 3. Conditional WGAN-GP on CelebA
**Objective:**
- Implement a Conditional GAN to generate images based on a label.
- Integrate labels into the generator and critic to guide image generation.
- Experiment with CelebA attributes (e.g., blonde hair or not).
- Analyze the quality of generated images based on the conditional labels.

Trained models are saved in the `models.zip` file.
