# Identify Boston Wetlands

![Wetlands Picture](https://user-images.githubusercontent.com/90286831/186621792-b537f1e2-11c4-43c0-8f3c-16a3f33c250c.png)

This project was undertaken as part of my stint as a Data Scientist with the City of Boston, Department of Innovation and Technology. 
Boston is facing climate related issues, such as extremely hot weather and risk of flooding, all of which can be mitigated by a natural resource 
present in the city, the wetlands. The goal is to help Boston's Environment Department to use satellite image data to identify wetlands and 
non-wetlands in the city, for better resource allocation by the city and the residents. 

This repository does not contain the image data used for training/testing the model. The code was implemented in Google Colab to use the free GPUs available for training the model. This implementation uses PyTorch framework to train a Convolutional Neural Network (CNN) model on images of wetlands and non-wetlands in Boston.

The output of this script is a web-application that serves the CNN model under the hood. It spits out the probability of an image being a wetland or non-wetland.

### Wetland Identification in Boston.pdf 
This file contains the presentation which was shared with the Department of Innovation and Technology's Analytics Team detailing the non-technical aspects of the project outline.

### Pretrained_Model_resnet34_JPG_Wetlands.ipynb
This is the script which sources the images, pre-processes the images, trains and tests the CNN model using PyTorch framework and serves the model on a web-interface
