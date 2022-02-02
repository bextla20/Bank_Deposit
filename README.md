# Bank_Deposit
Term deposits are a major source of income for a bank. A term deposit is a cash investment held at a financial institution. Your money is invested for an agreed rate of interest over a fixed amount of time, or term. The bank has various outreach plans to sell term deposits to their customers such as email marketing, advertisements, telephonic marketing, and digital marketing. Telephonic marketing campaigns still remain one of the most effective way to reach out to people. However, they require huge investment as large call centers are hired to actually execute these campaigns. Hence, it is crucial to identify the customers most likely to convert beforehand so that they can be specifically targeted via call.

# Dataset has 20 features
### Bank client data:

**Age**: Client’s age.

**Job**: Client’s type of job.

**Marital**: Client’s marital status, divorced means divorced or widowed.

**Education**: Client’s education.

**Default**: Client has previosly defaulted.

**Housing**: Client has a housing loan.

**Loan**: Client has a personal loan.



### last contact of the current marketing campaign:

**Contact**: Contact communication type (telephone or cellular).

**Month**: Last contact month of year.

**day_of_week**: Last contact day of week.

**duration**: Last contact duration in seconds. If duration is 0s, then we never contacted a client to sign up for a term deposit account.

**Pdays**: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

**Previous**: number of contacts performed before this campaign and for this client (numeric)

**Poutcome**: outcome of the previous marketing campaign (categorical: ‘failure’,‘nonexistent’,‘success’)


### Social and economic context attributes:

**Emp.var.rate**: employment variation rate - quarterly indicator (numeric)

**Cons.price.idx**: consumer price index - monthly indicator (numeric)

**Cons.conf.idx**: consumer confidence index - monthly indicator (numeric)

**Euribor3m**: euribor 3 month rate - daily indicator (numeric)

**Nr.employed**: number of employees - quarterly indicator (numeric)


### Target variable :

**y**:has the client subscribed a term deposit? (binary: ‘yes’, ‘no’)

**Confuison matrix*** of the dataset
![Confusion_matrix](https://github.com/bextla20/Bank_Deposit/blob/main/Confusion_matrix.png)

# Conculison
Gradient Boosting Classifier, AdaBoost Classifier and Random Forest score are more than 0.86.

Gradient Boosting Classifier score is 0.875 and with K-Fold is 0.882. While check with hyperparametrs, score is 0.870 and with K-Fold is 0.878. So Gradient Boosting Classifier score with K-Fold is better.

Ada Boosting Classifier score is 0.862 and with K-Fold is 0.870. While check with hyperparametrs, score is 0.869 and with K-Fold is 0.865. So Ada Boosting Classifier score with K-Fold is better.

Random forest score is 0.874 and with K-Fold is 0.876. While check with hyperparametrs, score is 0.879 and with K-Fold is 0.883. So Ada Boosting Classifier score with K-Fold is better.

Compare models Random forest husing hyperparameter tuning got high accuracy than others, we se that accuracy is **0.883**.
