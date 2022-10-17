# Neural_Network_Charity_Analysis

## Overview of the analysis: 
- Help the foundation predict where to make investments
- Use the features in the provided dataset to help create a binary classifier that is capable of predicting whether applicants will be successful if funded by Alphabet Soup

## Results: 
- What variable(s) are considered the target(s) for your model?
Looking to see if the target is marked as successful would indicate that it's been succesffully funded.
- What variable(s) are considered to be the features for your model?
The IS_SUCCESSFUL column
- What variable(s) are neither targets nor features, and should be removed from the input data?
EIN and NAME columns
- How many neurons, layers, and activation functions did you select for your neural network model, and why?
  Layer 1 - 120 neurons

  Layer 2 - 80 neurons

  Layer 3 - 40 neurons

  Layer 4 - 20 neurons

  Overall, sigmoid seemed to be a better fit for layers 3 (40 neurons). 
![Screen Shot 2022-10-17 at 12 50 43 PM](https://user-images.githubusercontent.com/107209737/196269810-03bc89a8-7a31-4bb1-ac68-e7308c11fe78.png)

- Were you able to achieve the target model performance?
No, the target was aout 73%
![Screen Shot 2022-10-17 at 12 54 05 PM](https://user-images.githubusercontent.com/107209737/196270405-67b02290-c8cc-4a26-9f9d-484719672a27.png)
- What steps did you take to try and increase model performance?
Columns were dropped and neurons were increased

## Summary: 
The activations produced about 73% accuracy. A random forest classifier could be tried because it may be less influenced by outliers.
