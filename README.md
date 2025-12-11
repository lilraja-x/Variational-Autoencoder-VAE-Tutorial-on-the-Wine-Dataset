# Variational Autoencoder (VAE) Tutorial on the Wine Dataset

Here, you’ll find everything you need to dive into using a Variational Autoencoder (VAE) with the classic Wine dataset. I put this together for a Machine Learning Techniques assignment, but it’s meant to be useful for anyone interested in VAEs. Inside, you’ll get:

- A full Jupyter Notebook that walks through VAE training and analysis
- A detailed academic report
- Visualizations from the trained model
- Code for reconstruction, exploring the latent space, PCA comparisons, and breaking down KL divergence
- All the files and instructions you need to reproduce the results from start to finish

---

## Project Overview

A Variational Autoencoder (VAE) is a generative model that creates a smooth, continuous latent space using a probabilistic encoder–decoder setup. In this project, you’ll see:

- How to prep and normalize numerical data for VAE training
- How the encoder learns both the mean and variance of latent variables
- How KL divergence keeps the latent space well-behaved
- What you can learn by looking at reconstructions and moving through the latent space
- How the VAE’s latent space stacks up against PCA

The model trains on the Wine dataset—178 samples, 13 chemical features, and 3 classes.

---

## Visualisations Included

Plot | What it Shows
-----|---------------
Training & Validation Loss | How the model learns over time
2-D Latent Space | How well classes separate visually
Reconstruction Errors | Where and how much the model misses
PCA Projection | A linear baseline for comparison
KL vs Reconstruction Loss | Breaks down the ELBO components
Original vs Reconstructed | Heatmaps to judge sample quality
Latent Traversal | Shows how the model decodes across the latent space

---

## References

- Kingma, D. P., & Welling, M. (2014). Auto-Encoding Variational Bayes.  
- Bishop, C. M. (2006). Pattern Recognition and Machine Learning.  
- Jolliffe, I. T. (2002). Principal Component Analysis.  

---
