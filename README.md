# deep-learning-examples
### Various examples in deep learning

# OVERFITTING
## Example of overfitting using a two-layer neural network, from overfit_demo.ipynb:

![alt text](misc/overfit.png)


# MNIST
## Example of clustering in the fc1 layer of the MNIST network defined in pytorch_mnist.ipynb.
### This is a 50-dimensional embedding space reduced to 2 dimensions by TSNE for plotting purposes. 
### This network achieves 98% accuracy.

![alt text](MNIST/mnist_layer_fc1_acc_98.png)

## Confusion matrices of training and testing data, respectively. 
### The row is the digit truth, the column is the digit prediction. 
### The accuracy is the sum of the diagonals divided by the total number of cases.
### In this case, the test confusion is slightly better than the train confusion.

![alt text](MNIST/train_confusion.png)
![alt text](MNIST/test_confusion.png)


## Example digits that have been correctly classified:
![alt text](MNIST/show_digits.png)


## Example digits that have been incorrectly classified:
![alt text](MNIST/show_errors.png)

