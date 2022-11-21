# Neural_Network_Charity_Analysis

The purpose of this analysis is to predict which companies to donate to based through a neural network analysis of past performance for previous donations.

## Results: 

## Data Preprocessing
- The target variable is the success variable.  This tells us whether a donation was deemed successful.

- All other variables are features in the model.  They include 
APPLICATION_TYPE            17
AFFILIATION                  6
CLASSIFICATION              71
USE_CASE                     5
ORGANIZATION                 4
STATUS                       2
INCOME_AMT                   9
SPECIAL_CONSIDERATIONS       2
ASK_AMT                   8747

What variable(s) are neither targets nor features, and should be removed from the input data?
The EIN and name should be removed from the input data.

## Compiling, Training, and Evaluating the Model
How many neurons, layers, and activation functions did you select for your neural network model, and why?
- I added another hidden layer, increased the neurons, and added a tahn activation function to my neural network model.

Were you able to achieve the target model performance?
- I was not able to achieve the target model performance.

What steps did you take to try and increase model performance?
- I tried removing the status column.

Summary: PCA could help determine feature importance so that the appropriate columns are removed for the neural network.
