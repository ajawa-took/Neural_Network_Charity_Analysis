# Neural_Network_Charity_Analysis


## Overview of the analysis

 A charitable foundation (Alphabet Soup Charity) that funds charitable organizations wants to predict the success of its grants. We build a deep-learning neural-network to model this.


## Results
### technical details about the models used


#### Data Preprocessing
 - The target variable that the model is trying to predict is IS_SUCCESSFUL
 - The feature variables used as inputs by the model are numerical STATUS and ASK_AMT, and categorical APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, and SPECIAL_CONSIDERATIONS.
 - Purely identifying variables EIN and NAME are are neither targets nor features, and should be removed from the input data.


#### Compiling, Training, and Evaluating the Model
 - All three of our attemps came close to, but did not achieve the target model performance of 75% accuracy. All were between 70% and 75%.
 - We considered network models with 2 or 3 layers, with 30 to 80 neurons per layer, using ReLU and tanh activations for the hidden layers and sigmoid activation for the output layer.
 - Varying the number of layers and the activation functions did not have much effect on model performance. Continued training also had very little impact on model performance. After 20-40 epochs, performance indicators bounced up and down instead of improving steadily. Even after the first two or three steps, the gains were marginal, e.g. improving from 72% to 74% accuracy (on training data).

