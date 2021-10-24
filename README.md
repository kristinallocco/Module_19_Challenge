# Neural Network Charity Analysis
24 Oct 2021

## Overview
The purpose of this analysis was to utilize deep learning models in an effort to aid AlphabetSoup, a philanthropic organization, to donating funds to applicant organizations that met their critera. The dataset contained information on over 30,000 prior donations as well as their outcomes. The model created binary classifications to deem whether or not future applicants would be successful if funds were allotted. The analysis first required preprocessing the data for the neural network, then compilation and training the model, and finally optimization. 

## Results

### Data Preprocessing
- What variables are considered the target for your model
  - The targeted variable is "IS_SUCCESSFUL"
- What variables are considered to be the features for your model
  - All but the "NAME" and "EIN" were features for the model 
- What variables were neither targets nor features and were therefore removed
  - "NAME" and "EIN" were not considered significant so they were removed from the model 

### Compiling, Training and Evaluating the Model
- How many neurons, layers and activation functions did you select for the neural network model 
- Was the model able to achieve target performance
- What steps were taken to try and increase model preformance 

## Summary
