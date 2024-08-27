# Crafting a Naïve Bayes model for predictive maintenance

This project aimed to implement a Naïve Bayes classifier from scratch on the “AI4I 2020 Predictive Maintenance Dataset Data Set”. The dataset explores the effects of various conditions on machine failure and what types of failures cause it to fail. Therefore, the objective is to determine the probability that a piece of equipment will fail due to root cause (c), where c covers all the causes of failure. 
- The dataset was first preprocessed where there are cleaning approaches and feature explorations applied before the model is fit and trained. 6000 Samples are taken for training and 2000 for testing. 
- A Gaussian Naïve Bayes classifier that takes ‘Failure Labels’ as the target and the features Type, air temp, process temp, rotational speed and torque was implemented. 
- Pre-processing, including binning, column transformation, creating new columns, and normalization were applied as necessary. 
- Data exploration involved label encoding, plotting bar graphs, box plots, and correlation heat maps.
- Performing the pre-processing steps resulted in an accuracy increase of 10%, going from 58% to 69% as it adjusted for skewness and removed outliers.
 
