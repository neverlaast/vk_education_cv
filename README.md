# VK Education: Computer Vision

My solutions to hands-on assignments from the VK Education Computer Vision program (Technopark, Bauman Moscow State Technical University).
The repository currently includes image classification on Fruits-360, comparing a custom CNN trained from scratch with a pretrained ResNet18 used as a frozen feature extractor.

## Assignments

| # | Topic | What was done | Result |
|---|-------|---------------|--------|
| [1](hw1.ipynb) | Image classification | Custom CNN vs. pretrained ResNet18 with a frozen backbone; Albumentations augmentations, a custom PyTorch training loop, learning rate scheduling, and early stopping | Test macro-F1: CNN = 0.9478, ResNet18 = 0.9877 |

## Stack

Python, PyTorch, torchvision, Albumentations, OpenCV, NumPy, scikit-learn, Matplotlib

