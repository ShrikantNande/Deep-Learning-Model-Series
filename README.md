# Deep-Learning-Model-Series
Deep Learning Model Series start from 1998 to 2021
## LeNet- 1998
The architecture consists of a total of 7 layers consisting- 2 sets of Convolution layers, and 2 sets of Average/Max pooling layers which are followed by a flattening convolution layer. After that, we have 2 dense fully connected layers and finally a softmax classifier.
![India](https://www.google.com/url?sa=i&url=https%3A%2F%2Fblog.csdn.net%2Fweixin_40756000%2Farticle%2Fdetails%2F113750137&psig=AOvVaw1YNGjGuCjnlXjIJSKyGSb-&ust=1613318514837000&source=images&cd=vfe&ved=2ahUKEwjEy5T5nefuAhVt_DgGHaUDAjUQjRx6BAgAEAc "Lenet")
The input used by LeCun was of the size (32 x 32) but as we will be using the MNIST dataset, so the image size in this dataset is (28 x 28). Thus, the input size we’ll be having is (28 x 28).
#### Observation
* Accuraracy is 0.9810.
* Loss is 0.0602.
* Prediction correct.
* Works well for MNIST Dataset.
* Simple and less complex structured conv layer model
