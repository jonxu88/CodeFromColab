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
