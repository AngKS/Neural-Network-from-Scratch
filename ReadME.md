# Building a Simple Neural Network from Scratch

[Video: Building a Neural Network from SCRATCH](https://www.youtube.com/watch?v=w8yWXqWQYmU)

[Dataset: Kaggle Digit Recognizer Dataset](https://www.kaggle.com/c/digit-recognizer/data)

The tutorial teaches you to build a simple Neural Network for the MNIST hand writing dataset using only Numpy, PANDAS and Matplotlib.

## Dataset
Each image is 28x28 pixels; with a total of 784 pixels per image in total. Each pixel has a pixel-value btween 0-255 (0 indicating that it is completely black, and 255 indicating that it is completely white)

## Pre-Processing
After using pandas to load the CSV dataset, I converted the pandas dataframe of values to a numpy array to uitilize the matrix functions of Numpy.

The dataset is first shuffle before being split into training and validation data.
- The training dataset has 41000 rows of data
- The validation dataset has 1000 rows of data

The data are all labelled with a label from (0 - 9) indicating the 10 different handwritten digits in the dataset.



## Neural Network
The Neural Network consists of 1 input layer, 1 hidden layer and 1 output layer.

