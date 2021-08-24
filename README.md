# Neural_Network_Charity_Analysis

## Overview 
Help Beks to create a binary classifier that is capable of predicting whether applicants will be sucessful if funded by Alphabet Soup

## Results
### Data Preprocessing
- Target variable is the IS_SUCCESSFUL columns, that will show this analysis goal for if the loan is sucessful or not.
- Features on our model are "APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, STATUS, INCOME_AMT, SPECIAL_CONSIDERATIONS, ASK_AMT"
- 'EIN' & 'NAME' columns are non-beneficial variable that dropped.

### Compiling, Training, and Evaluating the Model
- The model input data has 43 features and 25,724 samples, two hidden layers with 80 and 30 neurons respectively.
- **Sigmoid** is used for output layer since it is a binary classification.
- To speed up the training, activation function **Relu** used for hidden layers.
- The model result ![Original](https://github.com/jamesmoonusa/Neural_Network_Charity_Analysis/blob/main/Original%20Model%20Result.PNG)
- To improve the model increased number of neurons. 3 hiddden layers result![3 layers](https://github.com/jamesmoonusa/Neural_Network_Charity_Analysis/blob/main/3rd%20hidden%20layer%20result.PNG)

## Summary
