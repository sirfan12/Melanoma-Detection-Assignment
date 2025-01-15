# Project Name
> To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


- Provide general information about your project here.
In this assignment, we will build a multiclass classification model using a custom convolutional neural network in TensorFlow. 
  
- What is the background of your project?
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

- What is the business probem that your project is trying to solve?
 A model needs to be built to model the price of houses with the available independent variables. This model will then be used by the management to understand how exactly the prices vary with the variables. They can accordingly manipulate the strategy of the firm and concentrate on areas that will yield high returns. Further, the model will be a good way for management to understand the pricing dynamics of a new market.

- What is the dataset that is being used?
 The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

- Actinic keratosis
- Basal cell carcinoma
- Dermatofibroma
- Melanoma
- Nevus
- Pigmented benign keratosis
- Seborrheic keratosis
- Squamous cell carcinoma
- Vascular lesion


## Technologies Used
Python - version 3.11.7
Matplotlib - version 3.8.0
Numpy - version 1.26.3
Pandas - version 2.1.4
Seaborn - version 0.12.2
Tensorflow - version 2.15.1

## Conclusions 

The final model demonstrates a well-balanced performance, with no indications of underfitting or overfitting.

Incorporating class rebalancing has significantly improved the model's performance on both the training and validation datasets.

After setting to 30 epochs, the final model achieves an accuracy of 91% on the training set and approximately 83% on the validation set.

The minimal gap between training and validation accuracies highlights the strong generalization ability of the final CNN model.

Introducing batch normalization did not result in any improvement in training or validation accuracy.

# Acknowledgements
UpGrad , Statsquest, 3blue1brown, opensource community
