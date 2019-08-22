# Credit_Card_Overdue_ML
Taiwan Credit Card Company Dataset about Credit Card Overdue Problem

1. Visualize and check data distribution
2. Clean the data, remove the useless columns like ID
3. Use correlation matrix to see the colinearity among the variables
4. Check colinearity in the matrix using VIF
5. Colinearity suspected variables found, use seperated models to train the dataset with or without the suspected variables
6. Prepare the params for tuning using grid search in SVC, Random Forest, Decision Tree, KNN and XGBoost
7. Train the dataset with all the variables
8. Train the dataset without the suspected variables

Conclusion: Among the models, XGBoost did the best job in all the situations with 81.36% accuracy. And the dataset without suspected variables 
performed suspiciously better than others. Clearly overfitted. Cross Validation will be applied in the next step.
