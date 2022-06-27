# Credit Card Customer Churn Prediction

Data Source: [Click here](https://kaggle.com/sakshigoyal7/credit-card-customers?select=BankChurners.csv)

This dataset has a strongly imbalanced target variable, churned customer. It consists of 10,127 total number of customers with 1627 attrited customers which is 16.07% out of all customers. Thus, it will be an obstacle to train our model for predicting churning customers.

## Background
Acquiring a new customer can cost the credit card company 5 times more than retaining an existing customer. Also, existing customers tend to spend 31% more than a new customer and they are 50% more likely to try new products. More importantly, loyalty customers are profitable as the profits could increase up to 95% with 5% increase in retention rates. Losing a profitable long-term customer will decrease its customer base and lower its market share of the company. Thus, it will eventually lower its appeal so that it will be hard for the credit card company to cooperate with shops for promotion and hence it will be hard to attract new customers. Therefore, with a view to assist the credit card company to lower the credit card churn rate and lower the cost of operation and to retain existing customers to enable long-term customer relationship and to be a sustainable business, it is essential to have in-depth examination into the topic of credit card customer churn prediction.

## Project Goal
Predicting for the credit card company that a certain customer is at a very high risk of churning so that they can proactively go to the customer to provide them better product and service experience for retention so as to reduce the credit card churn rate and successfully achieve customer retention. The success metrics of this project is to achieve model accuracy that is better than the baseline.

## Hypothesis

If we could understand what features are related to customer churn and we could proactively deal with the related features, then we could reduce the customer churn for the credit card company.

## Project Process Flow

Step 1: Background & Business Problem

Step 2: About the Data

Step 3: Data Cleaning Process

Step 4: Exploratory Data Analysis

Step 5: Modeling

Step 6: Findings

## Methodologies 

With a view to comparing the performance of the model under different circumstances, I am going to apply the data into the model without doing any sampling techniques. Thus, I can see if applying sampling techniques can improve the performance.
Since the target variable is strongly imbalanced, it is assumed that simply applying the dataset into the model will result in overfitting and it will not be possible to predict who is going to be churned as the model will be biased as the major class is the existing customer. Therefore, my next approach is that I will try to apply undersampling using NearMiss method and oversampling using SMOTE method to balance the data and decide which sampling techniques have the best accuracy towards the predicted result.

## Findings

After comparing different models, it shows that XGBoost (eXtreme Gradient Boosting) performs the best. For the performance of the model to predict if the customer is churned, the precision score is 0.90, the recall score is 0.93, the f1-score is 0.92 and the average cross-validation score is 0.92. It shows that incorrectly predicting churned customers is only about 2%.
 
## Contact

Please feel free to contact me on [LinkedIn](https://www.linkedin.com/in/jennessa-lee/) if you like my project and would like to reach out, thank you!

