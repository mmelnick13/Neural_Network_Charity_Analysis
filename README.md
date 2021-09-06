# Neural Network Charity Analysis

## Overview of the analysis
Used machine learning and neural networks, and used the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup.

From Alphabet Soup’s business team, a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. Within this dataset are a number of columns that capture metadata about each organization, such as the following:
- EIN and NAME—Identification columns
- APPLICATION_TYPE—Alphabet Soup application type
- AFFILIATION—Affiliated sector of industry
- CLASSIFICATION—Government organization classification
- USE_CASE—Use case for funding
- ORGANIZATION—Organization type
- STATUS—Active status
- INCOME_AMT—Income classification
- SPECIAL_CONSIDERATIONS—Special consideration for application
- ASK_AMT—Funding amount requested
- IS_SUCCESSFUL—Was the money used effectively

## Results

### Data Preprocessing
- What variable(s) are considered the target(s) for your model?
  - The variable that was targeted was the 'IS_SUCCESSFUL' column.
  
- What variable(s) are considered to be the features for your model?
  - Considered every column in the dataset to feature in the model initially. The ones that ended up not being used were the ones that were dropped. 
  
- What variable(s) are neither targets nor features, and should be removed from the input data?
  - The varaibles that were not targeted note featured and dropped from the data was 'EIN and 'NAME'. Dropped because of the low impact these have on the data.

### Compiling, Training and Evaluating the Model
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  - This model is made with an input features & two hidden layers. The first hidden layer has 80 neurons, the second has 30 there is also an output layer. Each layer has an activation function. The first and second hidden layers have an activation function "relu" & the output layer is "sigmoid".
  
- Were you able to achieve the target model performance?
  - No, the target for this model was 75% or above, however was only able to get it to be 72%. It started with 46% and increased 26%. 
  
- What steps did you take to try and increase model performance?
  - Steps taken to increase the performance of the model were adding hidden layers, changing the activation type, changing the number of epochs and changing the number of neurons in each layer.

## Summary
The model accuarcay is 72%. While it is not 75%. It is possible the reason for this is we may have had to drop more features which may have affected how good the neural network actually is. The best way to increase the accuracy of your model is to have more data. If we have solid data added to this model, the accuracy of this model will be much more concrete.

