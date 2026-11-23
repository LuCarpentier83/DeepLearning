# Deep Learning

Hands-on deep learning notebooks with **TensorFlow / Keras**, from the first perceptron to GANs
and deep reinforcement learning. They follow the deep learning part of Aurélien Géron's
*Hands-On Machine Learning with Scikit-Learn, Keras and TensorFlow* (2nd edition), reworked
with my own notes and experiments.

## Contents

| Folder | Topics |
|---|---|
| `01_NeuralNet_With_Keras` | Perceptrons, activation functions, MLPs for classification and regression, Sequential / Functional / Subclassing APIs, saving models, callbacks, TensorBoard |
| `02_Training_Deep_Neural_Networks` | Vanishing / exploding gradients, Xavier & He initialization, Leaky ReLU / ELU / SELU, batch normalization, transfer learning, optimizers, regularization |
| `03_Training_with_TensorFlow` | Tensors and ops, custom losses, metrics, layers and models, autodiff with `GradientTape`, custom training loops, `tf.function` |
| `04_Loading_and_Preprocessing_Data` | `tf.data` input pipelines, preprocessing layers, TF Transform, TensorFlow Datasets, TensorFlow Hub |
| `05_Computer_Vision_with_CNNs` | Convolutions, pooling layers, CNN architectures, transfer learning with pretrained models |
| `06_Series_with_RNNs_and_CNN` | Time-series forecasting with simple and deep RNNs, LSTM, GRU and 1D convolutions |
| `nlp_with_rnns_and_attention.ipynb` | Char-RNN text generation, stateful RNNs, sentiment analysis, pretrained embeddings, encoder–decoder and attention |
| `08_Autoencoders_and_GANs` | Linear, stacked, convolutional, recurrent and denoising autoencoders, VAEs, GANs |
| `09_Reinforcement_Learning` | OpenAI Gym, policy gradients, Markov decision processes, Q-learning, DQN, TF-Agents |
| `00_Annexes` | Equation sheet and notes |

## Getting started

```bash
pip install tensorflow scikit-learn pandas matplotlib tensorflow-datasets tensorflow-hub
jupyter lab
```

Some notebooks need extra packages: `gym` and `tf-agents` for reinforcement learning,
`tensorflow-transform` for data preprocessing.
