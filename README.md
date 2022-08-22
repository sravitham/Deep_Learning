# Deep_Learning_Report

1. **Overview:** 
The nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success in their ventures. With knowledge of machine learning and neural networks, and the CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years, I will create a binary classifier that can predict whether applicants will be successful if funded by Alphabet Soup.


2. **Results**: 

  * Data Preprocessing
    1.  What variable(s) are the target(s) for your model?
        * IS_SUCCESSFUL is successful.
    2. What variable(s) are the features for your model?
        * APPLICATION_TYPE
        * AFFILIATION
        * USE_CASE
        * ORGANIZATION
        * STATUS
        * INCOME_AMT
        * SPECIAL_CONSIDERATIONS
        * ASK_AMT
        * CLASSIFICATION
    * What variable(s) should be removed from the input data because they are neither targets nor features?
        * EIN 
        * NAME
* Compiling, Training, and Evaluating the Model
    1.  How many neurons, layers, and activation functions did you select for your neural network model, and why?
        * Neurons: 110
        * Layers: two hidden layers using Relu.
    2. Were you able to achieve the target model performance?
        * No, the first run without optimization resulted in about 73% accuracy.
    3. What steps did you take in your attempts to increase model performance?
        * In order to increase model performance, only the Ein column was removed. Instead of 2 hidden layers, the second model had 4 hidden layers (2 relu, tahn, and sigmoid); this increased the accuracy to about 78%.

3. **Summary**: 
    * With an attempt to optimize the model I was able to reach 4-5% increase in accuracy of model from 73% to 78%.
