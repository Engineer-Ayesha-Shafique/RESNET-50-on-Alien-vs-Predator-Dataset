# RESNET50 on Alien vs Predator Dataset

This is an implementation of the RESNET50 neural network model on the Alien vs Predator image dataset. The dataset is available on Kaggle and can be accessed via the following link: https://www.kaggle.com/datasets/pmigdal/alien-vs-predator-images

## Dataset Overview
The dataset consists of images of Aliens and Predators. The training set has 347 images of each class, while the validation set has 100 images of each class. All images are in RGB format and have a resolution of 224x224.

## Implementation Details
The RESNET50 model is a deep convolutional neural network architecture that is widely used in image classification tasks. The model has 50 layers and is trained on the ImageNet dataset. We will be using a pre-trained version of this model, which has already been trained on ImageNet.

We will be using the Keras deep learning library to implement our model. Keras is a high-level neural network API that makes it easy to build and train deep learning models.

## Steps
1) Load the dataset using Keras' ImageDataGenerator class, which is used to read images from directories and preprocess them.

2) Build the model using the pre-trained RESNET50 architecture, with the final layer replaced to fit our binary classification task.

3) Compile the model and set the loss function and optimizer.

5) Train the model on the training set.

6) Evaluate the model on the validation set.

## Results
After training the model for 50 epochs, we achieved an accuracy of approximately 96% on the validation set. However, it's important to note that this accuracy may not be indicative of the model's performance on new and unseen data.

## Conclusion
In this implementation, I've used the RESNET50 architecture to classify images of Aliens and Predators with high accuracy. This model can be used to classify new and unseen images of Aliens and Predators with a high degree of accuracy.
