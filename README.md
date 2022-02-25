# Neural_Network_Charity_Analysis

## Overview of the analysis: Explain the purpose of this analysis.
  The purpose of this analysis is to create a machine learning that is able to accurately predict if a Charity is successful. 

## Results: Using bulleted lists and images to support your answers, address the following questions.

### Data Preprocessing
  - What variable(s) are considered the target(s) for your model? The target for the model is the 'Is_successful' field as that determines if the charity was overall successful.
  - What variable(s) are considered to be the features for your model?  The modelule had us focus on the application and classification. I would however say that ask_amt, use_case, and oraganization are most important for the model.
  - What variable(s) are neither targets nor features, and should be removed from the input data? EIN, Name, Status, and Special Considerations.
### Compiling, Training, and Evaluating the Model
   - How many neurons, layers, and activation functions did you select for your neural network model, and why? i used a total of 111 neurons and 3 total layers. I used this from the module as an intial base point when running the code. 
   - Were you able to achieve the target model performance? No.
   - What steps did you take to try and increase model performance? To attempt to increase perforamce i removed more column that i deemed were unnecessary, increase the number of layers to 5, as well as neurons to about 400. However with this i was not able to get the model performance to reach the goal of 75%. In one attempt i tried to run the model without the large number of $5000 ask amounts to see if that would help with a clearer result. 

### Summary: 
Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.
  Overall the results were that the model would be about 50% accurate when predicting success. There is a lot of noise wihtin the data so it would more than likely require much more cleaning and preprocessing with many trial and errors to be able to pinpoint the true data that will help the model predict with a higher success rate. 
