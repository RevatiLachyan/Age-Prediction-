# Age-Prediction
Convolutional Neural Network Application

A convolutional neural network is a feed-forward neural network that is generally used to analyze visual images by processing data with grid-like topology.
Unlike earlier computer vision algorithms, convolutional neural networks can operate directly on a raw image and do not need any preprocessing.

Question: 'Use this dataset to detect age: https://www.kaggle.com/datasets/arashnic/faces-age-detection-dataset. Build two deep models - one from scratch and the other using a pretrained model to obtain embeddings of the given data. Compare the performances.'

For Convolutional Neural Network from scratch, first imported data to data frame.
Then, converted the class variable as categorical to numerical data

Added input function, 3 relu layers, a flattening layer and a softmax function as an activation function

Model is fitted and the graph is plotted for the same.
The accuracy is 0.85.

![image](https://user-images.githubusercontent.com/114314499/219900667-0e430b48-51ee-48fe-b27c-8d7f788cb18e.png)


As the second step, the Mobile Net Network is applied.
For the fitting, weights is used as imagenet which means that we want to use the predefined ImageNet database as the weights.

The accuracy is 0.84.

![image](https://user-images.githubusercontent.com/114314499/219900646-a4df1c82-5770-4344-87c6-26ae4087f38e.png)

