# ResNets
ResNets y posibles modificaciones para clasificación CIFAR10 Y MNIST

Ejemplo ResNet56 extraída de Keras y modificaciones sobre esta arquitectura para una mejor precisión.

Modificación en de los bloques residuales introduciendo BatchNorm + Dropout bajos [Effective and Efficient Dropout for Deep
Convolutional Neural Networks](https://arxiv.org/abs/1904.03392) , así como la sustitución 
de la activación RELU por ELU.
