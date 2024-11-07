# ResNet Architecture from Scratch in PyTorch

This repository contains a custom implementation of the ResNet (Residual Network) architecture built from scratch using PyTorch. ResNet is a deep neural network designed to address the vanishing gradient problem, allowing effective training of very deep networks by introducing residual connections. This implementation supports multiple ResNet variants (ResNet-18, ResNet-34, ResNet-50) and is suitable for datasets like CIFAR-10 or ImageNet.
![image](https://github.com/user-attachments/assets/d97db310-0aa0-4606-9f45-bf4d5d5ebcfa)

# Architecture Overview
ResNet introduces skip connections to address the vanishing gradient problem, making it feasible to train deep networks. The main components include:

- Residual Block: A basic block with two convolutional layers and a skip connection.
- Bottleneck Block: Used in deeper ResNet architectures, uses 1x1 convolutions to improve efficiency.
- Downsampling: Achieved through stride-2 convolutions in residual blocks.
- Fully Connected Layer: For final classification tasks.
  
# References
- He, K., Zhang, X., Ren, S., & Sun, J. (2015). Deep Residual Learning for Image Recognition. In Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR).
- [ResNet Paper](https://arxiv.org/abs/1512.03385)
