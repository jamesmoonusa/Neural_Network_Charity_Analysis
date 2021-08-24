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
- The original model result ![Original](https://github.com/jamesmoonusa/Neural_Network_Charity_Analysis/blob/main/Original%20Model%20Result.PNG)
- Increaded hidden layer to 3 result.![3 layers](https://github.com/jamesmoonusa/Neural_Network_Charity_Analysis/blob/main/3rd%20hidden%20layer%20result.PNG)
- Increased Neurons to 100 and 40. ![More neurons](https://github.com/jamesmoonusa/Neural_Network_Charity_Analysis/blob/main/More%20neurons%20result.PNG)
- Increased Epochs to 150. ![150 Epoch](https://github.com/jamesmoonusa/Neural_Network_Charity_Analysis/blob/main/150%20Epoch%20train%20result.PNG)

## Summary
The deep learning neural model did not reach 75% of accuracy. Even after few attemps to increase the model performance as adding third hidden layer, increasing number of neurons and Epochs have insigificant result on the model accuracy.
So the model might not fit on the performance, alternatly supervised machine learning model might fit on this data becuase we are in a binary classification data.
