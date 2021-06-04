# Used Car Market

![alt text](https://images.unsplash.com/photo-1568605117036-5fe5e7bab0b7?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80)

## 1. Business Problem
The Used Car Market is a very importance business nowadays. Knowing the price of the car could be sold is a difficult task. So problem of the company is to know what is the correct price of car they can offer to their customers according to some characteristics of the automobile to maximize their profits and also don't get cheated by the buyers.

To goals of this project are:
- Understand what variables of the used car have the most influence on the price
- Predict the price of the used car according to their characteristics.

## 2. Solution Strategy
To solve the business problem of the bank, the following steps will be done:
- Data Description: Identify data contaning on the dataset provided by the company.
- Data Filtering: Filter rows and columns that do not contain information that matches the business problem.
- Data Cleaning: Check for null values and duplicated data and solve them.
- EDA: Explore the data to find insights and to understand how the variables impact the price of the used car.
- Feature Engineering: Convert the data into comprehensible information to the machine learning models.
- Machine Learning Models: Build machine learning models to predict the price of the used car.
- Avaliation of the Machine Learning results: Check the results provided by the models.
- Convert Model Performance to Business Values: Convert the performance of the Machine Learning Models into business results.

## 3. Top 3 Insights
- As newer the car is, higher it will be the price.
- Brands like Lamborghini, Bentley and Porsche have more expensive cars.
- Automatic car is approximately 3.7 time more expesive than manual cars.

## 4. Machine Learning Model Applied
It has tested a list of Machine Learning regression algorithms and the one with the best performance was chosen to be used in future predictions.

The chosen model was XGBoost.

## 5. Machine Learning Model Performance
| Model | R2 Adjusted Metric |
| ------- | ------- |
| XGBoost | 0.908 |

## 6. Business Results
According the dataset, the company has 6019 cars to be solded. It can be expected that with the analysis and prediction shown above, to company can increase 5% of their profit by selling the car with the correct price or even not getting cheated by the buyers. With of performance of metric of 90.8%, they can earn about $2,560,000.00 by the selling of all their used car with the correct price considering more 5% into their profit.

## Notebook solution of the problem
[Click here to see the notebook with the solution of this problem](https://github.com/Guilherme-Yuji/Data-Science-Portfolio/blob/main/usedCarMarket/Used%20Car%20Market.ipynb)
