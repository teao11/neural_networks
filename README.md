# neural_networks

# Overview
The purpose of this analysis was to allow us to leverage the tools that we had learnt throughout the final course module in neural nets. We were building neural net models to help create a binary classifier that was capable of predicting whether applicants will be successful if funded by Alphabet Soup.

# Results

## Data Preprocessing

What variable(s) are considered the target(s) for your model?
- Based on the prompt for the module challenge, I took the IS_SUCCESSFUL variable to be the target variable for my model.

What variable(s) are considered to be the features for your model?
- The other variables present were features in my model (excluding the name and EIN variables). We used one hot encoding to provide a new binary variable each unique integer value for variables that were categorical.

What variable(s) are neither targets nor features, and should be removed from the input data?
- We removed EIN and Name from our model.

## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why?
- For my model I used two hidden layers (due to seeing the output code for the challenge, I understood this was what it wanted). I chose the ReLu activation function because of its efficiency and simplicity (and I am most familiar with that!).

Were you able to achieve the target model performance?
- My first model achieved an accuracy of 0.72 but had a loss of 0.58 -- this sits just below the target of 75%

<img width="431" alt="Screen Shot 2021-10-08 at 10 31 52 AM" src="https://user-images.githubusercontent.com/46773181/136598821-919d5f59-d9d3-488c-892f-a4d144cad71c.png">

What steps did you take to try and increase model performance?
- I did not try and increase model performance! Due to other responsibilities I was not able to iterate here as much as I would have liked.

# Summary
All in all, we generated a model that was relatively accuracte and classifying whether applicants would be successful if funded by Alphabet Soup. Some future iterations for the model would include:
- Removing noisy variables
- Adding additional neurons to hidden layers
- Including additional hidden layers
- Changing the activation functions
