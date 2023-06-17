# DOPatch (distribution-optimized adversarial patch)
This repository contains the implementation code for the paper: Distributional Modeling for Location-Aware Adversarial Patches

By leveraging the distribution transferability of adversarial patches in placement locations, we propose distribution modeling to enhance the performance of location-aware patches. Through a distribution mapping network, we learn the adversarial position distribution of images on the surrogate model and further transfer the distribution prior to models in black-box settings, enabling efficient query-based patch attacks.

The code will be continuously improved

## ⚙️ 1. Prerequisites
- python >= 3.7
- torch >= 1.13.0+cuda11.6
- torchvision
- facenet-pytorch
- ...

## 🧾 2. Datasets
Please prepare the face dataset following the ImageFolder format, and place the dataset in *./data* folder (in this work we use LFW and CelebA)

