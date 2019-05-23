Small dataset Transfer Learning
============

A model of Deep Convolutional Neural Networks (CNN) based on transfer learning for image recognition.

This means to use a Deep CNN system pretrained on the large ImageNet dataset of 14 million images and 1000 classes in order to learn feature selection.

The results of the pretraining phase are transferred to the problem of classification for the images belonging to the UC Merced Land Use dataset with 21 classes.

There are specific cases where the image set used for training is orders of magnitude smaller than millions of samples, so how can effective performance be achieved from a deep neural network such as a CNN? One method that is used in the domain of Machine Learning is known as Transfer Learning, and it works by using a CNN trained on a large dataset to learn essential features that can be transferred to another related problem domain. The pretrained NN forms the base upon which a more refined network is trained on a smaller dataset specific to the new problem domain.

In image classification, Transfer Learning is expressed through the use of pretrained models. A pretrained model is a model that was trained on a large benchmark dataset to solve a problem similar to the one that one wants to solve. In accordance, due to the computational cost of training such models or the desired performance of classification, it is common practice to import and use models from published literature (e.g. VGG, Inception, MobileNet).

PyTorch ML framework and torchvision.models package are used.
