### Summary of the findings- 
The goal of this project is to compare the performance of the classifiers(k-nearest neighbor, logistic regression, decision tree, and support vector machines) to help bank managers prioritize and select the next customers to be contacted during bank marketing campaigns. 

In response, I analyzed the dataset thoroughly to understand the dependencies between the various features using different visualization techniques and evaluated various classification algorithms in terms of accuracy, precision, and recall scores. ROC curves were analyzed for SVC and Logistic regression classifier to determine the AUC values for the best classifiers. Using this approach the probability of success and failure of marketing campaigns could be accurately predicted. Finally, six different regression models were explored for the relationship between call duration and the various features of the dataset. Using this information banks can target the customers to call based on their profile and background information. 

### Conclusions
The following are the main attributes for the clients that are likely to sign up to make bank deposits-
1. Success rate is high for age groups below 30 yrs and above 60 yrs
2. Success rate is high for students (18.8%) and retirees (14.1%).
3. A higher balance (>5000 euros) translates to a higher probability of success. This trend is visible across various age groups.
4. The longer the call duration, the higher the probability of customer satisfaction and the chance of opening a deposit account.

##### Comparison of performance of the classifiers
Logistic regression and SVC have an accuracy of 89.4% (+/-0.39) and 89.5%(+/-0.4), respectively. The classification matrix indicated LR model has 91% precision for negative outcomes 55 % precision for positive outcomes and an AUC of 59 %. In comparison, the SVC model has 91% precision for negative outcomes 58 % precision for positive outcomes, and an AUC of 59%. Bank can use both SVC and Logistic regression to make predictions on the customers to call for the telemarketing campaigns.

##### Comparison of performance of the regression models
Out of 6 different models for predicting the call duration the logistic and ridge regression have the lowest negative mean square error. The use of regression models is expected to increase the efficiency of the bank's telemarketing campaign. Thus, saving both cost, effort, and resources for marketing.

#### Recommendations
To have a successful marketing campaign banks need to do the following- 
1. Target the right customers based on the classification algorithms
The bank can use machine learning models for classification to improve the efficiency in selecting the customers for the telemarketing calls. This is expected to lower the cost, and effort and reduce the imbalance in the original dataset presenting more accurate information for improving the subscription rate for bank deposits. 
2. Improve customer satisfaction
Using advanced data visualizations and analysis, the banks can understand the dependencies between the various customer attributes and changes of having a successful outcome for marketing campaigns. This will help to bank to provide better services for the customers in need (such as students and retirees who are more likely to make deposits). 
3. Timing, duration, and number of calls in the campaigns
The timing and duration of the marketing campaign play an important role when targeting customers for successful campaigns. The success rate of the marketing campaign is highest in March (over 50 %) and is it also high from Sept to December (i.e. over 40%). The probability of a client accepting to deposit at the bank goes down significantly beyond 5-10 calls. The longer the call duration, the higher the probability of customer satisfaction and the chance of opening a deposit account.

Location of datasets and script files-

Directories for Jupyter notebook
/bank+marketing/Practical Application Assignment 17_1_Comparing Classifiers.ipynb

Datasets
/bank+marketing/bank/bank-full.csv
/bank+marketing/bank/bank_cleaned.csv