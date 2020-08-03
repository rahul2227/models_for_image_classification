# models_for_image_classification

# Project Aimed:
Image classification is the process of taking an input (like a picture) and outputting a class (like “cat”) or a probability that the input is a particular class (“there’s a 90% probability that this input is a cat”).This project is made for classification of various images (like classification of different types of cars).This particular project is using fashion MNIST dataset for clothes as an input.

# Pre-Requisites:
Basic about Python3
Some of the Python Libraries
1.  numpy                       "https://numpy.org/"
2.  math                        "https://pypi.org/project/maths/"
3.  tensorflow_datasets         "https://pypi.org/project/tensorflow-datasets/"
4.  matplotlib      "https://pypi.org/project/matplotlib/"
5.  tensorflow      "https://pypi.org/project/tensorflow/"

# Installation:
There are some steps for installation
1.  Install Python3.                        "https://www.python.org/downloads/"
2.  Download and Install Anaconda Toolkit   "https://www.anaconda.com/products/individual"  
3.  Install Jupyter Notebook.                         
4.  Install all the libraries above mentioned by using "pip install library_name".
5.  Download the project. Run it in your system.


# Dataset:
The dataset used is Fashion_mnist from tensorflow datasets library, We can simply load dataset using {tfds.load('fashion_mnist', as_supervised=True, with_info=True)} after importing tensorflow_datasets as tfds.


# Algorithm:
In this we used a Deep Learning model using keras of tensorflow, This problem was approached using two neural network methods, In the first method only Dense layers was used with relu for optimizing our model for more efficiency acccurancy and better result in the second model integration of Convolutional neural networks (CNN) was done. In this model after using cnn a training accuracy of 97% and testing accuracy of 91% was achieved. 
