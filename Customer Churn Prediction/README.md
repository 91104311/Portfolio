# Customer Churn Prediction

## Overall Task:
Create a model to predict renewal likelihood (i.e. a retention model) and to know how likely to win each renewal opportunity in order to rank the renewal opportunity by risk. The final goal is to assign win probability for each unique opportunity.

## Datasets: 

There are two datasets. The first dataset consists of sampled renewal opportunities with renewal date in 04/2020, with each row representing a purchase line item in a renewal opportunity. This dataset came from a snapshot taken on the line items on the opportunity after the opportunity is closed.
Each opportunity can be uniquely identified by its ID (`renewal_id`). The renewal date (`renewal_date_c`) is populated by the renewal process. The date is supposed to be the earliest start date from the renewal lines that were loaded to the opportunity.
There could be multiple renewal opportunities under a sales account (`account_id`). An opportunity is then made up of purchase line items. Each purchase line item contains a product code (`product_code`), produce name (`name`), quantity (`quantity`), subscription start date (`start_date_c`), and subscription end date (`end_date_c`). 

The second dataset (event history data) contain the events triggered 6-12 months before the renewal date of an account. Each account may have multiple organizations. Organization can be created for a site geo or a project. An organization is an admin site where user account gets created. Each event is triggered by a user within or outside a project.

## Table of Contents:

### [1. Initialization](https://github.com/91104311/Portfolio/blob/main/Customer%20Churn%20Prediction/1.%20Initialization%20-%20Customer%20Churn%20Prediction.ipynb)

#### &nbsp;&nbsp;&nbsp;&nbsp; 1.1. Import Libraries
#### &nbsp;&nbsp;&nbsp;&nbsp; 1.2 Loading Data

### [2. Feature Engineering](https://github.com/91104311/Portfolio/blob/main/Customer%20Churn%20Prediction/2.%20Feature%20Engineering%20-%20Customer%20Churn%20Prediction.ipynb)

#### &nbsp;&nbsp;&nbsp;&nbsp; 2.1. Opurtunity Table
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.2. Event Table
#### &nbsp;&nbsp;&nbsp;&nbsp; 2.3. Combine Two Tables


### [3. Modeling](https://github.com/91104311/Portfolio/blob/main/Customer%20Churn%20Prediction/3.%20Modeling%20-%20Customer%20Churn%20Prediction.ipynb)

#### &nbsp;&nbsp;&nbsp;&nbsp; 3.1. Splitting
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.2. Sampling
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.3. Model Selection
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.1. Catboost
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.2. Logistic Regression
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.3. Random Forest 
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.4. Gradient Boosting
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.5. KNN
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.6. Stochastic Gradient Descent
##### &nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp; 3.3.7. Ada Boost Classifier
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.4. Comparison
#### &nbsp;&nbsp;&nbsp;&nbsp; 3.5. Most Important Feature Based on Random Forest

### [4. Forecast](https://github.com/91104311/Portfolio/blob/main/Customer%20Churn%20Prediction/4.%20Forecast%20-%20Customer%20Churn%20Prediction.ipynb)

### [5. Summary of the Results](https://github.com/91104311/Portfolio/blob/main/Customer%20Churn%20Prediction/Summary%20of%20the%20Results.pdf)

### [6. Future Work](https://github.com/91104311/Portfolio/blob/main/Customer%20Churn%20Prediction/5.%20Future%20Work%20-%20Customer%20Churn%20Prediction.ipynb)
