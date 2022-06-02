# Neural_Network_Charity_Analysis
## Overview of the loan prediction risk analysis:
Using machine learning and neural networks, and the provided dataset, I created a binary classifier capable of predicting whether applicants will be successful if funded by Alphabet Soup. The data was a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. In Deliverable 1, I preprocess the data for a Neural Network Model. For Deliverable 2, I compiled, trained, and evaluated the model. And for Deliverable 3, I optimized the model.

## Results:
### Data Preprocessing
The columns EIN and NAME were dropped.The target for our deep learning neural network was column IS_SUCCESSFUL. This column consisted of binary data on charity donations.The other columns: NAME, APPLICATION, TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT,SPECIAL_CONSIDERATIONS, STATUS, and ASK_AMT, were the features to this model.

### Compiling, Training, and Evaluating the Model
This model has two hidden layers with many neurons. The model accuracy is 73%. This is lower than the 75% I was tasked to receive so it doesnt really give me a good prediction on the outcome of the charity donations. Applying the feature ASK_AMT would have helped increased the number of neurons on a of hidden layers, making it a three hidden layers model.

## Summary
Unfortuantely, with this model, I did not reach our target of 75% accuracy, instead it was 73%. Probably, usnig another model such as: Random Forest model, would have been a better machine learning model to use for this analysis.
