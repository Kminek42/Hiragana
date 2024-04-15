<h1>hiragana NN</h1>

A neural network capable of recognizing 50 hiragana characters. Dataset sourced from https://github.com/inoueMashuu/hiragana-dataset. 

The dataset is divided into training, testing and validation in a 1:1:1 ratio. Each image is encoded using one hot encoding.

The neural network consists of several blocks. Each block consists of a convolutional layer, a maxpoll layer and an activation function. At the end is a single linear layer.

<img height="512" src="https://github.com/Kminek42/Hiragana/assets/51884463/30960004-e623-4901-8a6b-b7f34d2d2a76">

Despite the simplicity of the model, the results it achieves are quite good.

<img height="512 alt="image" src="https://github.com/Kminek42/Hiragana/assets/51884463/afedd303-51ce-4c37-99d6-330ae1799453">
