# PyTorch: CUDA vs CPU

## [Simple feedforward neural network (FNN)](./FNN.ipynb)

Here I trained the models for 100 epochs, with 64 batches of batch size 128

| device     | training time | difference    |
| ---------- | ------------- | ------------- |
| CPU        | ~21.9s        |               |
| GPU (cuda) | ~15.9s        | 37.27% faster |

## [Convolutional Neural Network (CNN)](./CNN.ipynb)

Here I trained the models on the MNIST dataset for 3 epochs, with a batch size of 16

| device     | training time | difference    |
| ---------- | ------------- | ------------- |
| CPU        | ~58.1s        |               |
| GPU (cuda) | ~47.3s        | 22.90% faster |

## TO-DO

- Recurrent Neural Network (RNN)
- Generative Adversarial Network (GAN)
- Autoencoder
- Transformers
