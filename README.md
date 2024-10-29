# Melanoma Detection Assignment
> To build a CNN based model which can accurately detect melanoma.A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.
- To create a CNN model, which can accurately detect 9 classes present in the dataset. While building the model, rescale images to normalize pixel values between (0,1)
- Rectify class imbalances present in the training dataset with Augmentor library.

## Conclusions
- In the first model created, there was an issue of overfitting. We resolved it using techniques such as augmenting images with various versions.
- In the second model, we saw an issue of underfitting. We also found the issue of class imbalance.
- Class imbalance issue was resolved by using an augmentor library which added almost 500 images to each class.
- In the third model, the issue of class imbalance and overfitting was resolved.

## Technologies Used
- Python - version 3.11.4
- Matplotlib - version 3.7.1
- Numpy - version 1.24.3
- Pandas - version 1.5.3
- Tensorflow - version 2.13.0

## Acknowledgements
Give credit here.
- UpGrad tutorials on Convolution Neural Networks (CNNs) on the learning platform

## Contact
Chandrika Sharma (chandrika.sharma09@gmail.com )