# colab-data-
Summary:

The analysis explores a telecom customer churn dataset. By building a model to predict churn based on customer behavior and service usage through the use of logistic regression, I was able to display and visualize the data set.

Key observations:

The dataset had 7043 records and 38 features. Noted there were significant values missing in columns like 'offer,' 'internet type,' and 'streaming services.' By use of imputation and label encoding for categorical values, I was able to handle the missing values.

model building:

For the categorical columns, I applied label encoding.
normalized the features using 'standard scaler.' 
the data was split into 80% training and 20% testing
This showcased a logistic regression model that was trained on the processed data.

Results:

Model accuracy: 79% 

Precision: 0.81

Recall: 0.76

F1 score: 0.78

Confusion Matrix: Shows minor false positives/negatives, indicating the model can improve.

Business Insights:

The churn is higher among customers with high monthly charges and short tenures. 

Its contract type heavily influences retention; those on month-to-month contracts churn more.

Clients using paperless billing and automatic add-ons churn less, thus suggesting that bundling services helps with retention.

What needs work:

The logistic regression is good, but its simplicity will prove challenging for complex churn patterns.

Consider more tree-based models for performance.

Reflection:

gained knowledge on cleaning and encoding a real dataset. 

application of machine learning to a real-life use case.

Host my code and present a real-life project.
#by lizzie chefpreneur
