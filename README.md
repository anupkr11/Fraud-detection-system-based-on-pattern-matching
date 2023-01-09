# Fraud-detection-system-based-on-pattern-matching

# Credit Card Fraud Detection

IMPLEMENTATION PART: 
- In this module, we'll gather all of the credit card data and save it to a folder. The dataset would then be subjected to descriptive analysis. 
- After reviewing the dataset, we must clean the data in the next phase. Both redundant values and null values in the dataset will be deleted during this cleaning step, and a new dataset will be created. 
- The cleaned dataset will be reprocessed in this module, with the dataset being grouped by volume and transaction period.
- The dataset will be split into two parts in this module: qualified dataset and testing dataset. The Random Forest Algorithm is used after the data has been partitioned. Finally, a confusion matrix is obtained after using the Random Forest Algorithm. Evaluation Now that the resulting data in the form of an uncertainty matrix has been obtained, it can be analyzed using a graphical representation, which provides greater precision


# FURTHER IMPROVEMENT
1. We have observed that the dataset which we are using from Kaggle which known as “CreditCard.csv’ is imbalanced i.e. it consist of 284315 non-fraud transactions and 492 fraud transaction.
2. So here, we can improve the recall and precision of our model by applying sampling techniques. 
3. There are 2 types of sampling 
  - Under Sampling 
  - Over Sampling
4. In the oversampling technique, samples are repeated, and the dataset size is larger than the original dataset. 
5. In the under sampling technique, samples are not repeated, and the dataset size is less than the original dataset.
6.We are implementing under sampling technique in our model, by choosing the no. of random samples from non-fraud transaction equals to number of fraud transaction in our dataset.
7. Concatenate both indices of fraud and non-fraud. 
8.Extract all features from whole data for under sample indices only.
9. Now we have to divide under sampling data to all features & target. 
10. Now split dataset to train and test datasets as before.
