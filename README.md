# ResNets
ResNets y posibles modificaciones para clasificación CIFAR10 Y MNIST

Ejemplo ResNet56 extraída de Keras y modificaciones sobre esta arquitectura para una mejor precisión.

Modificación en de los bloques residuales introduciendo data augmentation, BatchNorm + Dropout bajos [1] , así como la sustitución de la activación RELU por ELU [2].

[1][Rethinking the Usage of Batch Normalization and Dropout in the Training of Deep Neural Networks](https://arxiv.org/pdf/1905.05928.pdf)

[2][Fast and Accurate Deep Network Learning by Exponential Linear Units (ELUs)](https://arxiv.org/abs/1511.07289)
