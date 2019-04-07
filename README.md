# human-detection
Its deep learning problem to detect whether given image has human in it or not.

This problem is implemented using Convolution Neural Network using Keras.

Architecture followed in this convolution network is given below :

* Convolution 
* Pooling
* Convolution
* Pooling
* Fully Connected
* Relu
* Sigmoid

# Steps Involved :
1. Model first gets trained on 1800 images of human/non-human dataset.
2. CNN is compiled using Adam optimizer and metric is evaluated using cross entropy loss.
3. Then model is evaluated based on test dataset.
4. Finally when image is given, model will be able to predict whether image has human or not.


