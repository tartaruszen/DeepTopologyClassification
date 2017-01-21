# Deep Topology Classification

This repo contains code and datasets for the IEEE Big Data 2016 paper entitled - " Deep Topology Classification: A New Approach for Massive Graph Classification". It provides a feed forward neural network model for the classification of complex graphs based upon their feature vectors.

## Requirements

This code has been tested on Python 2.7.5+ and requires the following packages to function correctly:
* numpy 
* scipy
* graph-tool
* scikit-learn 
* tensorflow
* keras

This code function best when running upon a GPU via Tensorflow.

## Datasets

There are two datasets included in the python pickle format. One contains graphs from multiple graph generation methods and as such has multi classes contained within. The second dataset contains just two classes and as such is a binary dataset. 

Users own datasets can easily be used by generating fingerprint feature vectors from labelled graphs which you would like to be classified. A DTC model can then be trained.

## Native Tensorflow Implementation

There is an experimental implementation of DTC in native tensorflow. This code can be tested by running the *TF-Implementation.py* file via python. Please note that this is only for the multi-class dataset.   
