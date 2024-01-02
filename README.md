# Oxford IIIT Pet Dataset Classification with PyTorch

This repository contains a PyTorch implementation for classifying the Oxford IIIT Pet Dataset using K-Nearest Neighbors (KNN) and ResNet. The goal is to differentiate the results obtained using these two approaches.

## Dataset

The [Oxford IIIT Pet Dataset](https://www.robots.ox.ac.uk/~vgg/data/pets/) is a widely used dataset for fine-grained classification of pet images. It includes images of 37 different breeds of dogs and cats.

## Models Used

### K-Nearest Neighbors (KNN)

The KNN algorithm is employed for classifying the images in the dataset. The choice of K and other hyperparameters can be configured in the code.

### ResNet-34

We utilize the [ResNet-34](https://pytorch.org/vision/main/models/generated/torchvision.models.resnet34.html#torchvision.models.resnet34) architecture pre-trained on the ImageNet-1K dataset. This pre-trained model is used for linear evaluation and fine-tuning on the Oxford IIIT Pet Dataset.

## Collaborators

Special thanks to the following collaborators who contributed to this project:

- [Hiruni Wijewardena](https://github.com/Hiruni-Wijewardena)
- [Dilani Widanapathiranage](https://github.com/DNWidanapathiranage)
- [Chathuni Wijegunawardana](https://github.com/chathuni1999)
