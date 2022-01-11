# Evaluating membership inference attacks

These four jupyter notebooks implement classification tasks for Adult, MNIST, and CIFAR-10 (both with a small CNN and with a pretrained model).
Membership inference advantage is tested against different regimes of regularization and dropout, and against differential privacy for several values of epsilon.

Requirements:
- Python 3.8.10
- TensorFlow 2.5.0
- TensorFlow-Privacy 0.6.2
- *Optionally* CUDA 11.2
- Scikit-learn
- Pandas
