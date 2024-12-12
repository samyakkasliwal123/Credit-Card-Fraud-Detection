# Credit-Card-Fraud-Detection-ML
Credit Card Fraud Detection using Logistic Regression
* Skills - Logistic regression , Support Vector Machine, K Nearest Neighbours, F1 Score, ROC-AUC Curve, Data Visualisation , Exploratory Data Analysis , Data Science application in Finance , Machine Learning
* Tools - Google Colab , Jupyter Notebooks , Python , Numpy , Pandas , Matplotlib , Seaborn , Sklearn

# The Dataset :
The data was taken from Kaggle site : https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud .

The Columns do not have physical significance directly visible since as per the source (Kaggle) , the data was compressed using Principle Component Analysis (PCA) in order to protect the privacy of the individuals while making a realistic secnario dataset availaible to public .

# Data Preprocessing and Visualisation :

## Results from part 2 :
I have also uploaded some raw code to this repository, here are the conclusions derived from it :

Frauds are time-independent so we can drop time :


Lower Dimension Visualization is beautiful :

I also took advice from my seniors, decided to undersample the dataset since significance of the data would be more realistic if there was no synthetic dataset. I also decided to choose the ML model with most recall , reason being that I realized later that as a business, labelling a Non Fraud datapoint as fraudulent would be much more worse for the company, since nobody would like their card to decline and people would literally stop using that credit card, so we must focus more on achieving lower recall than only blindly improving F1 score . So I got Logistic regression as the winner again with the following results :

Other models weren't much far behind regarding performance too , but I decided to keep the final code clean and keep the trial and error part in the "raw_code" file .
