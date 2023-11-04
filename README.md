# Image Classification with ArcFace Loss Function Deep Learning
**Summary**
Here we are training a neural network to classify images from the CIFAR-10 & MNIST dataset using the ArcFace loss function. After training, it assesses the model's accuracy 
on the test data and provides class-specific accuracy metrics. The code demonstrates a comprehensive machine learning pipeline for image classification.

**Data Preparation:**
Importing necessary libraries and packages, including PyTorch, torchvision, and NumPy.
Defining device (CPU or GPU) for training.
Setting batch sizes and defining data transformations for the CIFAR-10 dataset & MNIST dataset.
Loaded the CIFAR-10 & MNIST training and testing datasets and set up the data loaders.
Defining classes for CIFAR-10 & MNIST categories and initialized the ArcFaceLoss for custom loss function.
Defined a neural network architecture (CNN) for embedding and classification.

**Training:**
Iteratively trained the neural network using the CIFAR-10 & MNIST training data, employing a custom loss function (ArcFaceLoss) and optimizing using Stochastic Gradient Descent (SGD). The training is carried out for 20 epochs, and loss per batch is tracked.

**Visualization:**
Visualized the training progress by plotting the loss per epoch in a graph.

**Model Evaluation:**
Evaluated the trained model's accuracy on the CIFAR-10  & MNIST test dataset.

Calculated and displayed the accuracy for each class within the dataset.
