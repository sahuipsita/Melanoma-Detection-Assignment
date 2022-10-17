# Project Name
> The assignment is to build a CNN based model which can accurately detect melanoma and to develop a solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- Developing a solution to detect skin cancer from images using convolutional neural network.
- Building a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 
- A solution would help in evaluating the images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
- Conclusion 1 from the analysis of Model-1 : The model was having higher training accuracy than validation set resulting in overfitting.
- Conclusion 2 from the analysis of Model-2 (using data augmentation and dropouts) : The model still was overfitting but the accuracy was better than Model-1.
- Conclusion 3 from the analysis of Model-3 (using Augmentor to rectify class imbalance, Batch normalization, dropouts : The model has better results after rectifying the class imbalance but still we see a difference of 10% difference in the accuracies.
- Conclusion 4 from the analysis of Model-4 (using data augmentation and using Augmentor dataset) : The model is best with good training and validation accuracy.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Python - version 3.7.3

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- References : referred session on neural networks


## Contact
Created by [@sahuipsita] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
