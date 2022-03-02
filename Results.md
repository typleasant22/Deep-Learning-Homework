
Report on the Neural Network Model

Overview

Alphabet Soup foundation wanted to create a algorithm to predict whether their applicants will be successful to fund them. We were provided a data set to create a binary classifier that would be capable of predicting whether the applicants would be successful if they were funded by Alhabet Soup.

Results
Data Preprocessing
1.What variable(s) are considered the target(s) for your model?

The target variable for our model is "IS_SUCCESSFUL", which declares if the money was susscessfully used or not.

2.What variable(s) are considered to be the features for your model?

The variables that are to be considered as features for the model were "APPLICATION_TYPE" and "CLASSIFICATION".

3.What variable(s) are neither targets nor features, and should be removed from the input data?

The variables that are neither targets nor features were "EIN" and "NAME". we used drop column to drop them from the data. 


Compiling, Training, and Evaluating the Model
1.How many neurons, layers, and activation functions did you select for your neural network model, and why?

I used 90 neurons with a tanh function for my first layer, 46 nuerons with a tanh function for the second, and 18 neurons with a tanh function for the third, and a sigmoid function for the outer layer.

2.Were you able to achieve the target model performance?

Unfortunely I was not able to achieve the target model performance.

3.What steps did you take to try and increase model performance?

I tried to increase my bin count and add an additional hidden layer to see if I could change the score. I stayed at 50 epochs because I wanted to stay low to really analyze the otucome.

Overall
The model still did not achieve the target model performance and resulted in an accuracy score of 73%.

I would recommend a classification model such as Logistic Regression due to the fact that we are trying to predict a discrete output of "whether applicants will be successful if funded by Alphabet Soup" (Yes/N
