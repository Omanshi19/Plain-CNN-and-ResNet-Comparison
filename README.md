This notebook implements and compares a plain deep CNN with a ResNet model on the CIFAR-10 image classification task.
The goal is to observe the effects of residual connections on training dynamics, accuracy, and generalization.

We will:

Load and preprocess CIFAR-10 data
Implement two models: Plain CNN and ResNet
Train both models under similar conditions
Plot and compare training/test accuracy and loss curves
Discuss observations and the importance of residual connections
