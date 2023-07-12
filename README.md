# FRM-Analysis (With Python and Grafana)

## The task

The purpose of the analysis is to develop a new strategy aimed at strenghtening customer relations with the company, by selecting the most valuable existing customers.
FRM analysis helps the business to group customers and develop more targeted marketing and customer service strategies to increase revenue.
The customer ranking is based on three major variables: Frequency, Recency and Monetary Value of purchase (Known as FRM Analysis).

The initial dataset had the following variables (columns): 
- DocumentId: Unique identifier of the sales document (text format)
- PartnerId: Unique identifier of the trading partner (text format)
- DocumentDate: Date of the sales document (date format)
- City: Headquarters of the trading partner (text format)
- Sales: Value of the sales document (numeric format)

![image](https://github.com/Fekete-Balazs710/FRM-Analysis/assets/117376416/f0a3f167-21e4-4afe-9dd9-738aae2c727b)


## The solution

> In order to solve the problem, I used Python with Jupyter Notebook to normalize dataframes, to calculate and add new variables to existing data and to create a scoring system. 
Later, I managed to create a Grafana dashboard to visualize the data and solution I provided.
All these components are part of a Docker container.

### 1. Frequency Analysis

Frequency shows the number of times a customer bought or interacted with the business during a specific period. 

![image](https://github.com/Fekete-Balazs710/FRM-Analysis/assets/117376416/2f93d1ef-7e9a-4e60-b8ed-27e5d7ac6cf8)


### 2. Recency Analysis

Recency indicates when the last purchase or contact was made by the customer.

![image](https://github.com/Fekete-Balazs710/FRM-Analysis/assets/117376416/fa3072f0-53aa-4c45-8281-d65f2dc04248)


### 3. Monetary Value Analysis

Monetary value shows how much money customers spend with the business.

![image](https://github.com/Fekete-Balazs710/FRM-Analysis/assets/117376416/de431767-a667-414e-bcb0-65d5343cbf91)


### 4. Visualizing the best ranked clients based on a scoring system

![image](https://github.com/Fekete-Balazs710/FRM-Analysis/assets/117376416/8b587499-cf11-4e14-9226-9be7074e6960)

![image](https://github.com/Fekete-Balazs710/FRM-Analysis/assets/117376416/eb6226f8-6b59-48d0-a1bd-e16f4704d784)

> The scoring system:
> ![image](https://github.com/Fekete-Balazs710/FRM-Analysis/assets/117376416/07e7ad8f-eff0-4a51-aba8-5aa3bf6a3862)





