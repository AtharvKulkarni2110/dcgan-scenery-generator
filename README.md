# dcgan-scenery-generator

# DCGAN Scenery Generator 🌄

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch to generate realistic **scenery/sky images** from random noise. It's designed as a deep learning project suitable for portfolio or resume showcasing.

## 🚀 Project Highlights

- Implemented a DCGAN from scratch using PyTorch
- Trained on a custom dataset of scenery images
- Includes training loop, loss tracking, and result visualization
- Customizable architecture for improved image quality

## 🧠 Architecture Overview

- **Generator**: Transposed Convolutional Neural Network to convert noise into scenery-like images
- **Discriminator**: CNN to distinguish real from generated images
- **Loss**: Binary Cross-Entropy (BCE) Loss

## 📦 Dependencies

Install via `requirements.txt`:


🧑‍💻 How to Run
Clone this repo:

```bash
git clone https://github.com/yourusername/dcgan-scenery-generator.git
cd dcgan-scenery-generator
```

Install requirements:

```bash
pip install -r requirements.txt
```

Open the notebook and run:

```bash
jupyter notebook DCGAN_project_pynb.ipynb
```

Optionally edit dataset path if training on a different dataset.


📈 Training Tips:
- You can improve results by increasing model capacity (more channels).

- Adjust latent space size (z_dim) and learning rates for experiments.
