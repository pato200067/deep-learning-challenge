# deep-learning-challenge
After creating the nn-model, here are my analysis on the performance of the model. A neural network model was created, futher adjustments were made to enhance the model's performance.
My target variable is the IS_SUCCESSFUL column with my final feature variables such as NAME, APPLICATION_TYPE, AFFILIATION, CLASSIFICATION, USE_CASE, ORGANIZATION, INCOME_AMT, ASK_AMT.
Thres variables EIN, SPECIAL_CONSIDERATIONS, and STATUS WERE REMOVED.
I created 3 layers for the final model with 100, 30, and 10 neurons respectively. I used the relu and sigmoid activation functions. Refer to the attached files for detailed results.
The model performance reached 80.75% accuracy exceeding the 75% target accuracy performance.

in summary, the final neural model could make predictions with 80% accuracy, this is higher than the performace of the original model which could only make predictions with 73%. This high performance was made possible 
by excluding variables such as SPECIAL_CONSIDERATIONS, AND STATUS from the final model. In addition more neurons were added to the model with sigmoid activation function.
Alternatively, I believe random forest model could be used. My attempt yielded a 78.2% accuracy. This is higher than the performance of the original model. 

I mimicked class activity and instructor demonstration code. I also used chatGPT for assistance. Browsed the net for codes when binning. 
