# Deep-Learning-Model-Series
Deep Learning Model Series start from 1998 to 2021
## LeNet- 1998
- The architecture consists of a total of 7 layers consisting- 2 sets of Convolution layers, and 2 sets of Average/Max pooling layers which are followed by a flattening convolution layer. After that, we have 2 dense fully connected layers and finally a softmax classifier.
![India](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTmTts1WlmhAqE6otE3zCr7lFb2l4El8uk53A&usqp=CAU "Lenet")
- The input used by LeCun was of the size (32 x 32) but as we will be using the MNIST dataset, so the image size in this dataset is (28 x 28). Thus, the input size we’ll be having is (28 x 28).
#### Observation
* Accuraracy is 0.9810.
* Loss is 0.0602.
* Prediction correct.
* Works well for MNIST Dataset.
* Simple and less complex structured conv layer model

## AlexNet- 2012
AlexNet proposed work has eight layers including five convolutional layers followed by three fully connected layers. Some of the convolutional layers of the model are followed by max-pooling layers. As an activation function, the ReLU function is used by the network which shows improved performance over sigmoid and tanh functions.
![India](https://miro.medium.com/max/3072/1*qyc21qM0oxWEuRaj-XJKcw.png "AlexNet")
Model Additional Features :
  1. Activation : Relu
  2. Dropout
  3. Local Response Normalization 
      - BatchNormalization is replace lrn
  4. Pooling
  5. Augmention
  6. GPU's 
#### Observation
* Training accuracy: 0.9925
* Training loss: 0.0237
* Validation Accuracy score : 0.6277
* Validation Loss : 2.0386
* Predictions : Not as we expected as we might need more amount of data or more layer training.
* Work's good for memorization but not as good as generalization
