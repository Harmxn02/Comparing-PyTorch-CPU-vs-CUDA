# PyTorch: CUDA vs CPU

The training for CUDA was done using a NVIDIA RTX 3060 Laptop GPU. The training for CPU was done using AMD Ryzen 5 5600H. Perhaps not a fair comparison, but those are the physical devices my laptop came with.

## [Simple feedforward neural network (FNN)](./FNN.ipynb)

Here I trained the models for 100 epochs, with 64 batches of batch size 128

| device     | training time | difference    |
| ---------- | ------------- | ------------- |
| CPU        | ~21.9s        |               |
| GPU (cuda) | ~15.9s        | 37.27% faster |

## [Convolutional Neural Network (CNN)](./CNN.ipynb)

Here I trained the models on the MNIST dataset for 3 epochs, with a batch size of 64

| device     | training time | difference    |
| ---------- | ------------- | ------------- |
| CPU        | ~58.1s        |               |
| GPU (cuda) | ~47.3s        | 22.90% faster |

## [Recurrent Neural Network (RNN)](./RNN.ipynb)

Here I trained the models on the MNIST dataset for 3 epochs, with a batch size of 64

| device     | training time | difference    |
| ---------- | ------------- | ------------- |
| CPU        | ~65.2s        |               |
| GPU (cuda) | ~45.8s        | 42.35% faster |

## [Generative Adversarial Network (GAN)](./RNN.ipynb)

Here I trained the models on the MNIST dataset for 3 epochs, with a batch size of 64

| device     | training time | difference       |
| ---------- | ------------- | ---------------- |
| CPU        | ~51.7s        |                  |
| GPU (cuda) | ~55.2s        | 6.40% **slower** |

## TO-DO

- Autoencoder
- Transformers
