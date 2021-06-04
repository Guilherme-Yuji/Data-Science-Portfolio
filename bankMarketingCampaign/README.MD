# Bank Marketing Campaign

[alt text](https://images.unsplash.com/photo-1488998527040-85054a85150e?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80)

## 1. Business Problem
Getting new clients or make their customers active is a extremely important task in any business because they impact on the revenue and growth of the company. In this project a bank company is using a marketing campaign strategy to raise the number of customers using their products and services and also try the convince the unative people to make a deposit into the bank. But problem is, what is the best strategy to achive this results? To solve this problem, the bank needs to understand what are the best strategies to use and who are main target person of the marketing. 

The goal of this project is:
- Make a marketing strategy to get more clients.
- Identify the main target of this campaign by the prediction of a deposit in the bank.

## 2. Solution Strategy
To solve the business problem of the bank, the following steps will be done:
- Data Description: Identify data contaning on the dataset provided by the company.
- Data Filtering: Filter rows and columns that do not contain information that matches the business problem.
- Data Cleaning: Check for null values and duplicated data and solve them.
- EDA: Explore the data to find insights and to understand how the variables impact the deposit action of the customer.
- Feature Engineering: Convert the data into comprehensible information to the machine learning models.
- Machine Learning Models: Build machine learning models to predict the deposit action.
- Avaliation of the Machine Learning results: Check the results provided by the models.
- Convert Model Performance to Business Values: Convert the performance of the Machine Learning Models into business results.

## 3. Top 3 Insights
By the analysis of the dataset provided, it can be concluded that clients that make a deposit in this bank have the following characteristics:
- Age about 20 years old and older than 60 years old.
- Are students
- People with low balance and lives in loan houses.

## 4. Machine Learning Model Applied
It has tested a list of Machine Learning classifier algorithms and the one with the best performance was chosen to be used in future predictions.

The chosen model was Gradient Boost

## 5. Machine Learning Model Performance
| Model | Accuracy Metric |
| ------- | ------- |
| Gradient Boost | 0.807 |

## 6. Business Results
According to the dataset, 5873 customers did not make a deposit in the bank on the last year. This value represents 52.6% of the total clients.

If the company had done earlier this analysis, they could make about 50% of the people that did not make a deposit make. Knowing the the algorith has 80.7% of accuracy, about 2370 could be convinced or start business with bank, making a deposit. If they deposit a least $50 for month, the company would have gotten a total of $1,422,000.00 in a year into their company to invest on their necessities.

## Notebook solution of the problem
[Click here to see the notebook with the solution of this problem](https://github.com/Guilherme-Yuji/Data-Science-Portfolio/blob/main/bankMarketingCampaign/Bank%20Marketing%20Campaign.ipynb)
