Hand on Neural-Network

	Coding from scratch for those who are new to Neural Network like me.. :) :p
	
	This repo includes the basic code to use python with tensorflow/keras for Neural Network 
	implementation.

	The codes or the methods are implemented using CS231n course of Standford University.
	
Network Layer Parameters:
	
	1. Input Layer: It depends upon the shape of training data. The number of feature column is equal to 
	the number of neurons in that layer. To provide flexibility in the network or to overcome the network
	from being dead due to zero inputs in between, the bias term is used.
	
	2. Output Layer: It depends upon the type of model configuration.If our model is regression model then
	the output layer will have only one output node and if our model is based on classification then the 
	number of output layer is the number of classes or number of different labels. So, it is completely 
	depends upon the type of model we have chosen.
	
	3. Hidden Layer: This is the most important portion of the Neural Network. There is no hard and fast 
	rules in choosing number of neurons and number of hidden layers. But, if we follow some of the basic
	tricks or techniques then the modle accuracy can be very much affected. So, here is the techniques/tricks:
	
	If our dataset is linearly seperable then twe don't need any hidden layers and we don't need any Neural 
	Network at all to resolve the task. But if the dataset is not linearly seperable then we do need a Neural 
	Network with proper configuration. Therefore, the optimal size of hidden layer is in between the input 
	layer and output layer. 

Transfer Learning:

	When the developed machine learing model is used to develop some other machine learning models, the new model
	that learnt from the first model is known as the transfer learning.
	
	It is a well known approach in deep learning where the pre-trained machine learninig models are used as the 
	ignitition point or the starting point for the new machine learning models.
	
	For eg. in Convolution Neural Network sometime we used to choose the pre-trained models such as ImageNet, ResNet 
	etc. for our new model. So, this comes under transfer learning.
	
	For further reading on transfer learning visit the following site: 	
https://machinelearningmastery.com/transfer-learning-for-deep-learning/
