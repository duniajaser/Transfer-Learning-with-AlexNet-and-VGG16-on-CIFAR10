# Transfer-Learning-with-AlexNet-and-VGG16-on-CIFAR10

This repository hosts the code and brief discussion related to the application of transfer learning techniques using AlexNet and VGG16 on the CIFAR10 dataset. This case study is part of the ENCS5141—Intelligent Systems Laboratory course at Birzeit University.

## Project Overview

The project explores transfer learning with AlexNet and VGG16 models, pre-trained on the ImageNet dataset, to classify images from the CIFAR10 dataset. It investigates two main transfer learning strategies:
1. **Finetuning**: Where all pretrained weights are updated.
2. **Fixed Feature Extractor**: Where all layers except the last fully connected layer are frozen.
