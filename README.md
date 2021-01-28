# Alien_VS_Predator
# ANN-V.S.-CNN

# Objective
The objective of this project is to compare the performance of basic models of ANN and CNN with the bare minimum of image preprocessing on the Alien vs Predator dataset

# Data
Alien and Predator images (JPG, various), for transfer learning. Split into Keras folder structure.
•	Format: JPG images, various thumbnail sizes (around 250 x 250 px).
•	The train file contains of two classes that is aliens and predators containing 247 images each.
•	The test file contains of two classes that is aliens and predators containing 100 images each.

Data link : https://www.kaggle.com/pmigdal/alien-vs-predator-images

# Image Pre-processing
Image pre-processing enhances some image features important for further processing. The steps of Image pre-processing used in this project are reading the Image, resizing the image, rescaling the image.

# Image Classification Techniques
The most common Image classification techniques are using Convolutional Neural Networks and Artificial Neural Network. 

•	CNN’s are regularized versions of multilayer perceptrons. CNN uses relatively little pre-processing compared to other image classification algorithms. CNN has two layers viz convolutional layers and pooling layers. In a CNN, the input is a tensor with shape (number of images) x (image height) x (image width) x (input channels(RGB, Grayscale etc). Convolutional networks may contain pooling layers to reduce the dimensions of the data by combining the output of neurons to a single neuron in the next layer. Max pooling uses the max value of each cluster of neurons at the prior layer.

•	ANN are built like the human brain with neuron nodes interconnected with each other. ANN are implemented as a system of interconnected processing elements called nodes. The connections between different nodes have a numerical value called weights and by altering these values in a systematic way the network is eventually able to do the desired function. The hidden layers can be thought as feature detectors, for example if the network is given a task to recognize a car, the first hidden layer might act as a line detector, the second hidden layer takes lines as input and puts them together to form a tyre, then in the third layer it forms the structure. This hierarchy enables the network to eventually recognize very complex objects as well.

# Results
CNN(Train_Accuracy) - 89.07,
CNN(Test_Accuracy) - 85.51,
ANN(Train_Accuracy) - 75.8,
ANN(Test_Accuracy) - 73.11.
