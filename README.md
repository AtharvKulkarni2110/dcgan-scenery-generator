# DCGAN Scenery Generator 🌄

This project implements a Deep Convolutional Generative Adversarial Network (DCGAN) using PyTorch to generate realistic **scenery/sky images** from random noise. It's designed as a deep learning project suitable for portfolio or resume showcasing.

## 🤖 What is DCGAN?

**DCGANs (Deep Convolutional GANs)** are a special kind of GAN that replaces fully connected layers with convolutional layers, making them highly effective for image generation tasks. They use:

- A **Generator** network to learn how to create fake images
- A **Discriminator** network to distinguish between real and fake images
- Both networks train together in a mini adversarial game

![DCGANS_results](https://github.com/user-attachments/assets/9c1dd275-53a9-4f0c-b608-27d4fc0018dd)




## 🚀 Project Highlights

- Implemented a DCGAN from scratch using PyTorch
- Trained on a custom dataset of scenery images
- Includes training loop, loss tracking, and result visualization
- Customizable architecture for improved image quality

## 🧠 Architecture Overview

- **Generator**: Transposed Convolutional Neural Network to convert noise into scenery-like images
- **Discriminator**: CNN to distinguish real from generated images
- **Loss**: Binary Cross-Entropy (BCE) Loss


## 📊 Results

Below is a sample output after training for 100 epochs:

| **Epoch** | **Generated Images** |
|-----------|-----------------------|
| 20        | Basic blurry shapes   |
| 50        | Clearer structure     |
| 99        | Realistic scenery! 🌅 |



![Screenshot 2025-06-25 234405](https://github.com/user-attachments/assets/791b60ce-0533-4be7-8098-144aa7ad12e8)
![Screenshot 2025-06-25 234425](https://github.com/user-attachments/assets/191a1ae3-3bfc-4fd9-9342-ee97185e34cd)


---
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

📄 License
MIT License – free to use, modify, or build upon!
