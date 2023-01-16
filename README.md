# Melanoma Detection assignment

> **Problem statement:** To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

The data set contains the following diseases:
  - Actinic keratosis
  - Basal cell carcinoma
  - Dermatofibroma
  - Melanoma
  - Nevus
  - Pigmented benign keratosis
  - Seborrheic keratosis
  - Squamous cell carcinoma
  - Vascular lesion
  
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

- The accuracy of test set is around 94%
- Accuracy of validation dats set is around 85%
- We may run extra epochs to see if the model performs better. But, in such case there could be a problem of overfitting as well.
- The model with the above accuracy shows an increased performace of the model when we train with dataset where number of images in each class is balanced.
- We can see that the model performed better on augmented data.
- After 10 epochs validation loss tends to slight increase and traning loss was decrease

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- [Python - Version 3.9.7](https://www.python.org/download/releases/3.0/)
- [numpy - Version 1.20.3](https://github.com/numpy)
- [pandas - Version 1.3.4](https://github.com/pandas-dev/pandas)
- [matplotlib - Version 3.5.1](https://github.com/matplotlib)
- [seaborn - Version 0.11.2](https://github.com/seaborn)
- [Jupyter Notebook - Version 6.4.5]
- [Anaconda - Version 2.2.0]
- [tensorflow]

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- The project reference course details from upGrads .
- PI session and Live presention about the brief of the project [Manish]

## Created By 
- [Manoj Bisht](https://www.linkedin.com/in/manoj-bisht-b293a657/)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->