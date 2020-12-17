# MNIST-Image-Classification---Tensorflow-and-Keras
This repository contain development of deep net which helps in image classification of MNIST handwritten image from 0 to 9
https://archive.ics.uci.edu/ml/support/Pen-Based+Recognition+of+Handwritten+Digits

Steps being followed-
1. Import libraries

2. Import dataset

3. Normalizing the data

4. Build the model
Input layer - It contains 28*28 = 784 neurons which is further flattened from 2-dimensional
Hidden layer 1 - The hidden layer has 64 neurons with relu as the activation function
Hidden layer 2 - The hidden layer has 64 neurons with relu as the activation function
Output layer - The layer has 10 neuron as there are 10 classifiers (0 - 9) with softmax function, which will give probabilities for each class. And the class with highest probability is given as output

5. Compile the model
Optimizer - adam will help in generating optimal weights, learning from previous weights. Another method is gradient descent for generating optimal weights
Cross entropy - It helps in generating maximum probability for the correct classifier, after running epochs and iterations. This reduces the loss function
Accuracy - It helps in understanding how good and reliable is the model.

6. Train the model
The model is fitted into the train models with 5 epochs. 1 epochs contain 784 iterations.

7. Evaluate the model - Output


Important points being considered:
1.	The color ranges from 0 to 255 (by default)
2.	The pixel of square are 28*28 = 784 pixel
3.	For applying deep learning, the image which is two dimensional has to get flattened.
4.	Since there are 784 pixels in the image, there would be 784 neurons in the input layer.
5.	There would be 10 neurons in the output layer as there are 10 classes (0 to 9)
6.	Hidden layer with relu as the activation function
7.	The pixel which contain labels are bound with weights, while the pixel without labels are weightless, in deep nets.
8.	The class with highest probability is identifies as the class for given image – softmax function.

