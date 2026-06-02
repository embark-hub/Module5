This assignment for Module 5 is titled: 
Evaluation Evaluation of two machine learning models to predict long hospital stay in patients with diabetes

Abstract:
Longer length of stay in hospital increases the risk of certain adverse events for patients and has negative impacts on hospital flow.  Using the Diabetes 130-United States (US) hospitals for years 1999-2008 dataset, I evaluated two machine learning models to see how well they were able to predict long hospital stay, defined as 4 days or more.  A total of 101,766 records with 50 features were pre-processed and analysed. The random forest model performed marginally better than the logistic regression model, with area under the receiver-operator curve (AUC-ROC) of 0.82 for predicting hospital stay of 4 days or more, compared to the logistic regression model with an AUC-ROC of 0.81.  The features with the highest importance in predicted longer hospital stay were number of medications and number of laboratory tests.  The analysis was limited as only records from inpatient stays from 14 days or less were obtained. More recent data from inpatient stays greater than 14 days would help to develop these models further.


Link to original dataset (also contained within the code) posted here in case: https://archive.ics.uci.edu/dataset/296/diabetes+130-us+hospitals+for+years+1999-2008

Please run python code in google colab.
Python version 3.12
