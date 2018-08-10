# Toy CNN to classify squares vs circles

## About
This project is a simple refresher on CNNs. The goal is to classify squares vs circles. The data is generated via scripts. A random selection of them is chosen to train the CNN.

## Files 
 + CircleMaker.ipynb - Makes circles
 + SquareMaker.ipynb - Makes squares
 + BuildDataset.ipynb - Builds dataset out of squares and circles
 + CircleSquareClassifier.ipynb - CNN classifier
 
## Understanding
Since the project is as simple as it gets, the model is also very simple. There are 2 convolutional layers and 3 dense layers. The parameters generated in the process are from the convolution layers. This is the point of learning in this project. For a problem of such scale, too many parameters are unnecessary.

## Requires
 + Tensorflow-gpu >=1.8
 + Numpy
 + cv2