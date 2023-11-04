# CIFAR-100 

## Homework Assignment for CECS 551 Advanced Artificial Intelligence

### Objectives of the Assignment:
1. Design a convolutional neural network to classify CIFAR-100 images using the keras library. 

### The CIFAR - 100 Dataset
The dataset contains 100 classes containing 600 images each. There will be 500 training images and 100 testing images per class.
The dataset can be found: https://www.cs.utoronto.ca/~kriz/cifar.html here.
The 100 classes in the CIFAR-100 are grouped into 20 superclasses. Each image comes with a "fine" label (the class to which it belongs) and "coarse" label (the superclass) it belongs to.

    1a. Goal: Divide the dataset even further to include a validation dataset. This is to be able to achieve a better generalization error for the overall training model.
        Because this model has a relatively low amount of images per class, we must consider methods to improve the generalization error. 
    1b. The neural network will be designed to identify the "fine" label. 
2. Model Experimentation: We should experiment with various combinations of activations, optimizers, hyper-parameters, architectures within the model
3. Model Selection: Using the sub-training and validation data set, we identify the three most effective models.
4. Full training: Retrain these top three models using the entire training dataset
5. Accuracy testing: We calculate and compare the test accuracy of each of these three models using the test dataset.
6. Report: Write a comprehensive report detailing the optimzers, hyper-parameters, and architecutres in your best three models. 

The report will be found in this repository. The Jupyter notebook cifar100.ipynb will hold the raw code used to do the assignment. 