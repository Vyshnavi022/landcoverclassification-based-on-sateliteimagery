A proposal to build a Convolutional Neural Network that classifies photos into predetermined 
categories via the use of filters. The satellite images are archived in EuroSAT and Google Earth 
Engine datasets which we import and use to train our model. We use Keras API on top of 
TensorFlow and max pooling algorithms for dimensionality reduction and feature extraction. The 
project is constructed in Google Colab/Jupyter Notebook. After labeling the training data we use 
the satellite images to label land cover. Max pooling layers containing filters/kernels are integrated 
into the CNN architecture to down sample the feature maps obtained from convolutional layers. 
At the end of the code, it will return composite images obtained by applying CNN layers and the 
classification result. This classification result can be applied in Environmental Monitoring, Urban 
Planning and Development, Agricultural Management, Natural Resource Management, Disaster 
Management, Wildlife Habitat Mapping, and more. 
