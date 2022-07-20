# Deep Learning - Melanoma Detect Assignment
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information.
- The main aim is to build a multiclass classification model using a custom convolutional neural network in TensorFlow. 
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant. 

## Conclusions
- Using droput Layer and Data augmentor help to reduce the overfitting.
- Handling class imbalnced helped to increase the overall model accuracy but there is a sign of overfittin. 
- we need to use dropout regularization on rebalanced data to avoid overfitting in data

## Technologies Used
- Tensor Flow library is main technology used for CNN model building

## Acknowledgements
- This project was inspired by upgrad.
- tensorflow official site helped to understad some concepts more clearly.
