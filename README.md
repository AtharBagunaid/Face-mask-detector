# face mask recognition for COVID-19
This repository contains the source code of face mask recoginition model. This model is built using a a keras built in model called vgg16. It is pre-trained convolutional neural network model. 

## Dataset
the dataset used in this model is downloaded from Kaggle website. This dataset contains in total 7450. Half of them with_mask and the other half without_mask.
I divided the dataset into 3 folders
- train
- valid
- test

each of the 3 folders contains the 2 folders 
1. with_mask
2. without_mask
----------------------------------------------------------
data/train/with_mask/... contains 2,347 images with mask 

data/train/without_mask/... contains 2,347 images without mask

	        --------------------

data/valid/with_mask/... contains 261 images with mask

data/valid/without_mask/... contains 261 images without mask

		--------------------

data/test/with_mask/... contains 1,117 images with mask 

data/test/without_mask/... contains 1,117 images without mask

--------------------------------------------------------------
### The link to dataset
	
	https://www.kaggle.com/omkargurav/face-mask-dataset

### Sample of input data
![sample](https://github.com/AtharBagunaid/Face-mask-detector/blob/main/1.png.jpg?raw=true)

## The objective of this project is:
To build a model that enable the computer to recognize individuals who are/are not following precaution of wearing face mask in public areas.
