
Project description:

	Customers have started to leave "Beta Bank". Every month, a few leave, but it is noticeable. Bank marketers have calculated that it is cheaper to retain current customers than to attract new ones.

Task:
	The task is to predict whether a customer will leave the bank in the near future or not. Historical data on customer behavior and termination of contracts with the bank is provided.
Goal:
	Build a model with the highest possible F1 score. To pass the project successfully, the metric should be brought to 0.59. Test the F1 score on the test dataset and examine the AUC-ROC.

Description of the project data structure:

Features:

1. RowNumber - index of the row in the data;
2. CustomerId - unique customer identifier;
3. Surname - surname;
4. CreditScore - credit rating;
5. Geography - country of residence;
6 Gender - gender;
7. Age - age;
8. Tenure - how many years a person has been a bank customer;
9. Balance - balance on the account;
10. NumOfProducts - the number of bank products used by the customer;
11. HasCrCard - the presence of a credit card;
12. IsActiveMember - client's activity;
13. EstimatedSalary - estimated salary.

Target feature:
1. Exited - fact of the customer leaving.

Path to the solution:

1. Data exploration and pre-processing;
2. Testing models without considering class imbalance;
3. Working with class imbalance, selecting a method to deal with it;
4. Retesting the models;
5. Selection of the most accurate model.

Models tested include:

1. Decision Tree;
2. Random Forest;
3. Logistic Regression.

Results:

1. The F1 score of the model was 0.61;
2. The density of the model was also 0.61.
