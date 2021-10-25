# Neural Network Charity Analysis
24 Oct 2021

## Overview
The purpose of this analysis was to utilize deep learning models in an effort to aid AlphabetSoup, a philanthropic organization, to donating funds to applicant organizations that met their critera. The dataset contained information on over 30,000 prior donations as well as their outcomes. The model created binary classifications to deem whether or not future applicants would be successful if funds were allotted. The analysis first required preprocessing the data for the neural network, then compilation and training the model, and finally optimization. 

## Results

### Data Preprocessing
- What variables are considered the target for your model?
  - The targeted variable is "IS_SUCCESSFUL"
- What variables are considered to be the features for your model?
  - All but the "NAME" and "EIN" were features for the model 
- What variables were neither targets nor features and were therefore removed?
  - "NAME" and "EIN" were not considered significant so they were removed from the model 

### Compiling, Training and Evaluating the Model
- How many neurons, layers and activation functions did you select for the neural network model?
  - This model utilized two hidden layersn the first with 80 neurons and the second 30 neurons. Also included was an output layer as well as each layer having an activation funtion. The first activation function is "relu" and the second and output are "sigmoid.
  - <img width="600" alt="Screen Shot 2021-10-24 at 8 11 08 PM" src="https://user-images.githubusercontent.com/85713470/138618380-9ac4dda6-bc7b-4197-9453-50d233c55877.png">
  - The base model achieved an accuracy of 53.2%
   - <img width="600" alt="Screen Shot 2021-10-24 at 8 15 01 PM" src="https://user-images.githubusercontent.com/85713470/138618501-82f765d7-3858-4930-9890-05a426117b0a.png">

- Was the model able to achieve target performance
-
- What steps were taken to try and increase model preformance 

## Summary
