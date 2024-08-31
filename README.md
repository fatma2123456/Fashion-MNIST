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


## Results Visualization 🧐
The script plots the accuracies of DNN and CNN models across different bootstrapping estimators, allowing for comparison of model performance.

## 
