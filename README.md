# Handwriting-Recognition
This project aims at the image classification of handwritten digits. We have 60,000 training images and 10,000 testing images. 
Tha problem:

Classification of Handwritten Digits 0 - 9 

The dataset: 

The MNIST dataset will be used more information here: http://yann.lecun.com/exdb/mnist/

Preprocess of the dataset

 The images are being normalized in the scale [0, 1]
 
Architecture of the Model:

1. A Flattened Layer the input is being flattened
2. A Dense Layer with 512-units and Relu activation fucntion
3. A Dense Layer with 10-untis and Softmax activation function

The model is compiled with Sparse Categorical Cross Entropy as lost function and  Adam as optimizer.  
The model is trained for 10 epochs.  
