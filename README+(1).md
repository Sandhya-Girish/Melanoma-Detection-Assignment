# Melonama Detection Assignment
> Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. 
It accounts for 75% of skin cancer deaths. 
Hence a solution is needed which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual 
effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Problem statement: To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths
- Solution : A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- Dataset used is 'CNN_assignment.zip' which contains The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. It contains 9 classes of diseases. 


## Conclusions
- Conclusion 1 : Model#1 is created with 4 CNN layers and without drop-out. However, there is a problem of overfitting observed. Hence, it is decided to add the dropout layer in the model
- Conclusion 2 : Model# 2 is created with 4 CNN layers alongwith the dropout layer. It seems to solve the problem of overfitting, however, there is a class imbalanace observed where the number of image is not uniform across the 9 classes of diseases. Also, accuracy is low.
- Conclusion 3 : Mode#3 is created by using the augmentor to resolve the problem of class imbalance by distributing 4500 images across the 9 classes. Following observations are made -
1. The model is doing well with respect to overfitting & class imbalance.
2. Accuracy is slightly increased by using augmentor
3. The problem of overfitting can be solved by add more layer,neurons or adding dropout layers.
4. The Model can be further improved by tuning the hyperparameter

## Technologies Used
- Notebook - Python version at Google Colab is used for the execution of the models


## Acknowledgements
Give credit here.
- This project was inspired by the assignment created by upgrad under the Deep Learning module


## Contact
Created by [@Sandhya-Girish] - feel free to contact me!

