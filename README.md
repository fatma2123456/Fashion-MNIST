# Fashion MNIST Dataset 


## Description
This project focuses on processing and analyzing the Fashion MNIST dataset using Python. It includes tools for loading, visualizing, and preparing the data for machine learning tasks, particularly image classification,And This project implements an ensemble model combining Deep Neural Networks (DNN) and Convolutional Neural Networks (CNN) for classifying images from the Fashion MNIST dataset. The ensemble uses bootstrapping to create multiple estimators and averages their predictions for improved accuracy.

## Table of Contents
<ul>
  <li><a herf="i"><h4><b> Installation </b> </h4> </a> </li>
  <li> <a herf="v"><h4><b> visualize </b></h4></a> </li>
  <li><a herf="c"><h4><b> Code Structure </b></h4></a></li>
  <li><a herf="f"><h4><b> Features </b></h4></a> </li>
</ul>

## Installation 🔽

I load The Data for My Backup and i install and work from drive on colap,and this is easy becuse this save a data,
and don`t upload this agin.

## visualize 🙈

Load and visualize data.

## Prepare the data 👩‍🍳

<h4><b>First</b></h4>
Collect Pixels in CSV into images then , Each image has a label.
<h4><b>Second</b></h4>
Collect all images have a same lable in folder , so , i have 10 lables i have 10 floders : from 0 ---->>> 9 .
<h4><b>Third</b></h4>
I split the Train Dataset ---->>> Train and validation Dataset and put the Validtion data to anthor folder ,
becuse I would used in the next step .


## Dataset
<ul>
<li><b>Training set</b>: 48,000 images</li>
<li><b>Validation set</b>: 12,000 images</li>
<li><b>Test set</b>: 10,000 images</li>
</ul>

## Code Structure 🤕

<ul>
  <li><b>create_data_generators()</b>: Creates data generators for validation and test sets.</li>
  <li><b>create_dnn_model()</b>: Defines the Deep Neural Network model.</li>
  <li><b>create_cnn_model()</b>: Defines the Convolutional Neural Network model.</li>
  <li><b>bootsrbing_ensemble()</b>: Implements the bootstrapping ensemble method.</li>
</ul>


## Model Architecture 
<ol>
  <li><b>DNN Model</b>:</li>
  <ul> 
    <li>Flattened input</li>
    <li>Dense layers (128 units, 64 units)</li>
    <li>Output layer (10 units for 10 classes)</li>
  </ul>
  <li><b>CNN Model</b></li>
  <ul> 
    <li>Convolutional layers (32 filters, 64 filters)</li>
    <li>Max pooling layers</li>
    <li>Flattened layer</li>
    <li>Dense layer (64 units)</li>
    <li>Output layer (10 units for 10 classes)</li>
  </ul>
</ol>


## Results Visualization For Bootstrpping on Validation Dataset 🧐
The script plots the accuracies of DNN and CNN models across different bootstrapping estimators, allowing for comparison of model performance.


<a href="https://github.com/fatma2123456/Fashion-MNIST/blob/main/Fashion_MNIST_Dataset.ipynb"><img src="https://github.com/fatma2123456/Fashion-MNIST/blob/main/Bootsrapping.png" alt="Result Bootstaping"></a>


## Results Form DNN and CNN Model On Training Dataset 🤦

<h4><b>DNN Model</b>:</h4>
<ul>
  <li>Final Training Accuracy: 0.9191</li>
  <li>Final Validation Accuracy: 0.8173</li>
  <li>Test Accuracy: 0.8238</li>
  <li>Precision: 0.7584</li>
  <li>Recall: 0.7548</li>
</ul>

<h5><b> Results Visualizations DNN Model</b>:</h5>

<a href="https://github.com/fatma2123456/Fashion-MNIST/blob/main/Fashion_MNIST_Dataset.ipynb"><img src="https://github.com/fatma2123456/Fashion-MNIST/blob/main/DNN%20Confusion%20Matrix.png" alt="DNN confusio matrix"></a>

<h4><b>CNN Model</b>:</h4>
<ul>
  <li>Final Training Accuracy: 0.9590</li>
  <li>Final Validation Accuracy: 0.8932</li>
  <li>Test Accuracy: 0.9034</li>
  <li>Precision: 0.9033</li>
  <li>Recall: 0.9034</li>
</ul>

<h5><b> Results Visualizations CNN Model</b>:</h5>

<a href="https://github.com/fatma2123456/Fashion-MNIST/blob/main/Fashion_MNIST_Dataset.ipynb"><img src="https://github.com/fatma2123456/Fashion-MNIST/blob/main/CNN%20Confusion%20Matrix.png" alt="CNN confusio matrix"></a>


<h4><b> Results Visualizations For Comparision CNN and DNN model</b>:</h4>


<a href="https://github.com/fatma2123456/Fashion-MNIST/blob/main/Fashion_MNIST_Dataset.ipynb"><img src="https://github.com/fatma2123456/Fashion-MNIST/blob/main/comparision%20of%20DNN%20and%20Cnn%20Loss%20.png" ></a>


<a href="https://github.com/fatma2123456/Fashion-MNIST/blob/main/Fashion_MNIST_Dataset.ipynb"><img src="https://github.com/fatma2123456/Fashion-MNIST/blob/main/comparision%20of%20DNN%20and%20Cnn%20Precision%20and%20Recall%20.png" alt="Result Bootstaping"></a>

## Thank You For Reading The README i hope you will use this for Understands The code 🥰
