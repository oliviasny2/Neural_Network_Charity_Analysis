# Neural_Network_Charity_Analysis

## Overview of the Analysis
The purpose of this analysis is use neural networks and deep learning models to determine if a charity qualifies for funding through Alphabet Soup

## Results

### Data Preprocessing
* What variable(s) are considered the target(s) for your model?

The target variable for the model is "If Successful."

* What variable(s) are considered to be the features for your model?

With the exception of the identifying variables, all variables are included in the preliminary run. This includes Application Type, Affiliation, Classification, Use Case, Organization, Status, Income Amount, Special Considerations, and Ask Amount

* What variable(s) are neither targets nor features, and should be removed from the input data? 

Only the identifying variables were excluded. These were the EIN and Name variables

### Compiling, Training, and Evaluating the Model

* How many neurons, layers, and activation functions did you select for your neural network model, and why?

During the preliminary run, there were 75 neurons, 2 hidden layers using the relu activation function with the output layer using the sigmoid activation function. In the following runs, 75 neurons were in the input, 3 hidden layers, with two using the relu activation function and one using the leaky relu function, with the sigmoid activation function as the output function. Adding the additional hidden layer and changing the activation function were in an attempt to increase the accuracy of the model.

* Were you able to achieve the target model performance?

No. The accuracy only increase slightly, by what I would consider a statistically insignificant amount

* What steps did you take to try and increase model performance?

Reducing the number of variable that were run through the model (removing the Affiliation, Organization, and Use Case variables), adding an additional hidden layer, and changing the activation function used in the hidden layers.

## Summary 

The overall results is that the accuracy falls around 53% and the loss around 0.69. Using the Random Forest model could provide a different perspective and perhaps an easier classification model. Logistic Regression may also simplify the model used.
