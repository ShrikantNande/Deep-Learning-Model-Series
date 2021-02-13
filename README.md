# Deep-Learning-Model-Series
Deep Learning Model Series start from 1998 to 2021
## LeNet- 1998
The architecture consists of a total of 7 layers consisting- 2 sets of Convolution layers, and 2 sets of Average/Max pooling layers which are followed by a flattening convolution layer. After that, we have 2 dense fully connected layers and finally a softmax classifier.
![India](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTmTts1WlmhAqE6otE3zCr7lFb2l4El8uk53A&usqp=CAU "Lenet")
The input used by LeCun was of the size (32 x 32) but as we will be using the MNIST dataset, so the image size in this dataset is (28 x 28). Thus, the input size we’ll be having is (28 x 28).
#### Observation
* Accuraracy is 0.9810.
* Loss is 0.0602.
* Prediction correct.
* Works well for MNIST Dataset.
* Simple and less complex structured conv layer model
