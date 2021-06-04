# Bank Client Churn

## 1. Business Problem
Churn of clients is a growing problem in this bank company and as a result, the profit of the company is decreasing. The directors of the bank are worried about the falling financial results of the business. 

To prevent the lost of a customer and also all the consequences mentioned above, the bank is trying to understand what factors influence clients to quit or stop using their products and services. Another objetive of the bank is to try to predict if a customer has a high to churn and also get some informantion of the kind of Persona that has this tendency of stopping using the bank services.

## 2. Solution Strategy
To solve the business problem of the bank, the following steps will be done:
- Data Description: Identify data contaning on the dataset provided by the company.
- Data Filtering: Filter rows and columns that do not contain information that matches the business problem.
- Data Cleaning: Check for null values and duplicated data and solve them.
- EDA: Explore the data to find insights and to understand how the variables impact the churn rate.
- Feature Engineering: Convert the data into comprehensible information to the machine learning models.
- Machine Learning Models: Build machine learning models to predict the churn.
- Avaliation of the Machine Learning results: Check the results provided by the models.
- Convert Model Performance to Business Values: Convert the performance of the Machine Learning Models into business results.

## 3. Top 3 Insights
By the analysis of the dataset provided, it can be concluded that clients that churn in this bank have the following characteristics:
- Credit card limit lower than 5K.
- Do around 40 transations a year.
- Have 2 or 3 products held of the bank.

## 4. Machine Learning Model Applied
It has tested a list of Machine Learning classifier algorithms and the one with the best performance was chosen to be used in future predictions.

The chosen model was Gradient Boost

## 5. Machine Learning Model Performance
| Model | AUC Metric |
| ------- | ------- |
| Gradient Boost | 0.945 |


## 6. Business Results

