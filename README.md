# RNN-based-Leo-Tolstoy-langauge-model
Implementation of a recurrent neural network for predicting the next character in a given sentence. 

The training dataset used here is the book War and Peace by Leo Tolstoy.
The text file of the book can be downloaded from [HERE](https://raw.githubusercontent.com/mmcky/nyu-econ-370/master/notebooks/data/book-war-and-peace.txt)

Each character is converted into its one-hot encoding. An RNN is then trained with one hidden layer which predicts the one-hot vector of the next characteras output, given the past sequence. This corresponds to the operations.
![image](https://user-images.githubusercontent.com/38180831/205384906-37d1f1df-38c4-4a3e-b8f2-e98096c68fde.png)


