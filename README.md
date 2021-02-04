# Project_Banana_Classifier.ipynb
Given a picture of a banana, classify it as green, overripe, or ripe. Can try using MobileNetV2, ResNet50, and VGG16.
This is code following a code along run by Jackie Tan, from UpLevel's Data Science Code-Along. 
See https://www.eventbrite.com.au/x/pythondl-code-along-is-my-banana-ripe-yet-tickets-138204999875

# BasicConvnetOnMNIST.ipynb
Basic Convnet on MNIST, validation accuracy approx 0.98.

# RecurrentNeuralNetworks.ipynb
Recurrent Neural Network on MNIST, following Sentdex's youtube video. Validation accuracy = 0.98

# TensorFlowClassification2VGG16.ipynb
Implementation of the VGG16 network (from scratch) to be trained on the CIFAR10 dataset. Test accuracy= 0.81 (compared to 0.68 on a basic Convnet). My understanding is that there should be some image pre-processing done first...?

# TensorFlowClassification2VGG16UsingAPI.ipynb
Implementation of the VGG16 network (from Keras) on the CIFAR10 dataset. However, we keep the pre-trained weights (done on ImageNet) of the convolutional layers and only train the final three dense layers.
Test accuracy: 0.63

# JonModifiedTensorFlowTutorialBasicClassification.ipynb
In order to learn the implementation of a convolutional network, I added some convolutional layers
to the Basic Classification Exercise given in the keras tutorial: https://www.tensorflow.org/tutorials/keras/classification
As well, some hyperparemeters were altered to see how they affected accuracy.

# TensorFlowClassification2
Basic Convnet on the CIFAR10 dataset. Test accuracy = 0.68

# TensorFlowClassifcation3
Basic Convnet on the CIFAR100 dataset
