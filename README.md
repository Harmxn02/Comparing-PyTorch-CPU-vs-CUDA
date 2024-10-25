# PyTorch: CUDA vs CPU

> To compare both devices, I trained a models for 100 epochs, with 64 batches of batch size 128

## [Simple feedforward neural network (FNN)](./FNN.ipynb)

| device     | training time | difference    |
| ---------- | ------------- | ------------- |
| CPU        | ~21.9s        |               |
| GPU (cuda) | ~15.9s        | 37.27% faster |

## TO-DO

- Convolutional Neural Network (CNN)
- Recurrent Neural Network (RNN)
- Generative Adversarial Network (GAN)
- Autoencoder
- Transformers
