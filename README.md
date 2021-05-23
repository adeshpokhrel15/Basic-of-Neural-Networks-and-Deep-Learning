# Neural-Networks-and-Deep-Learning
## Neural-Network:
Neural networks are computing systems with interconnected nodes that work much like neurons in the human brain. Using algorithms, they can recognize hidden patterns and correlations in raw data, cluster and classify it, and – over time – continuously learn and improve.

## Deep-Learning:
Deep learning (also known as deep structured learning) is part of a broader family of machine learning methods based on artificial neural networks with representation learning. Learning can be supervised, semi-supervised or unsupervised.
<br>
#### <img src= https://res.cloudinary.com/adeshpokhrel/image/upload/v1621659278/NNDL_yjymlc.png height=500 width=900></br>

## 1.Building an Image Classifier Using the Sequential API
### Using Keras to Load the Dataset: 
Keras provides some utility functions to fetch and load common datasets. Every image is represented as am array rather than a 1D array of size. Moreover, the pixel intensities are represented as integers from (0 to 255) rather than floats (from 0.0 to 255.0)

When the dataset is already split into a training set and a test set, but there is no validation set, so let’s create one. Moreover, since we are going to train the neural net‐work using Gradient Descent, we must scale the input features. For simplicity, we just scale the pixel intensities down to the 0-1 range by dividing them by 255.0 (this also
converts them to floats).
We need the list of class names to know what we are dealing with it.
 
 
## Building a Regression MLP Using the Sequential API
Building, training, evaluating and using a regression MLP using the Sequential API to make predictions is quite similar to what we did for classification. The main differences are the fact that the output layer has a single neuron (since we only want to predict a single value) and uses no activation function, and the loss function is the
mean squared error. Since the dataset is quite noisy, we just use a single hidden layer with fewer neurons than before, to avoid overfitting.

However, although sequential models are extremely common, it is sometimes useful to build neural networks with more complex topologies, or with multiple inputs or outputs. For this purpose, Keras offers the Functional API.

# 2.Training Deep Neural Networks
<img src=https://res.cloudinary.com/adeshpokhrel/image/upload/v1621736019/TraininNN_xjmqzj.png>
 


