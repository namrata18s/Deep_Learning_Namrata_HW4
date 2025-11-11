# Deep_Learning_Namrata_HW4

# GANs on CIFAR-10 (DCGAN / WGAN / WGAN-GP / ACGAN)

This repository implements and compares **DCGAN**, **WGAN**, **WGAN-GP**, and **ACGAN** on the CIFAR-10 dataset using PyTorch.  
The project trains each GAN variant, logs losses, saves generated image samples, and outputs loss curves suitable for homework reports or research experiments.

---

## 🚀 Features

- ✅ Train **DCGAN**, **WGAN**, **WGAN-GP**, and **ACGAN**  
- ✅ CIFAR-10 dataset with automatic download and preprocessing  
- ✅ Saves:
  - Generated sample grids per epoch 
  - Loss curves per model
  - Checkpoints for Generator/Discriminator 
- ✅ Combined generator/discriminator loss plot  
- ✅ Jupyter-friendly training 
- ✅ CSV logging for losses  

---

## 📦 Installation

```bash
pip install torch torchvision matplotlib
