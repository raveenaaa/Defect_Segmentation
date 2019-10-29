# Defect_Segmentation
This repository contains a model to detect defects by Industrial Optical Inspection on Textured Surfaces. 

### Data
* The first six out of ten data sets are used for training while the last 4 are used for testing. 
* The training set consists of 1000 non-defective and 150 defective images while the test set consists of 2000 non-defective and 300 defective images. 
* The images are saved in grayscale 8-bit PNG format.
* The code makes use of a compressed version of the data which can be found [here](https://drive.google.com/file/d/1w-P1hpF8FUo4nVBL5uAkgi7H0gTFQlq8/view) 
* Actual data can be downloaded from [here](https://hci.iwr.uni-heidelberg.de/node/3616)

### Model
* The underlying model is based on the following paper [U-net: Convolutional Networks for Biomedical Image Segmentation](https://arxiv.org/abs/1505.04597)

