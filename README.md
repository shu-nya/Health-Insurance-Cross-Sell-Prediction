# Health-Insurance-Cross-Sell-Prediction

An Insurance company that has provided Health Insurance to its customers. Now it wants to find out whether its customers from past year will also be interested in Vehicle Insurance provided by the company.

# Project Goal

Building a model to predict whether a customer would be interested in Vehicle Insurance is extremely helpful for the company because it can then accordingly plan its communication strategy to reach out to those customers and optimise its business model and revenue.

# About the Data 

We have the data of which contains details of customers like id , age, gender and also contains the details of the customers vehicle.

# Features information

The dataset contains features like:

id :- Unique ID for the customer

Gender :- customers’ gender

Age :- Age of the customer

Driving_License :- Customer is having driving license or not

Region_Code :- Unique code for the region

Previously_Insured :- Whether the customer has insured previously or not

Vehicle_Age :- Age of the Vehicle

Vehicle_Damage :- Is the customer got his/her vehicle damaged in the past

Annual_Premium :- The amount customer needs to pay as premium in the year

PolicySalesChannel :- Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.

Vintage :- Number of Days, Customer has been associated with the company

Response :- The customer is interested or not

Target Variable :

Response :- The customer is interested or not

# Project Work flow

Importing Libraries

Loading the dataset

Data Summary

Data Cleaning & Data Analysis

Feature selection

Implementing Various Classification Algorithms

HyperParameter Tuning

Final selection of the model

# Conclusion

From this dataset of health insurance customers almost 95% of customers have a vehicle age that's less than 2 years. from our analysis, customers who has more than 2 years of vehicle age are more interested with vehicle insurance advertisment, while customers who has less then one year of vehicle age, only 4% of them are actually interesred with vehicle insurance

We found out that customer who already have vehicle insurance are almost have no interest in another vehicle insurance. Our analysis shows that 99.9% of customers that have a vehicle insurance is not interested in another vehicle insurance, while customer who doesn't have a vehicle insurance 22.5 % of them are interested with vehicle insurance

We also found out that a newer vehicle are more likely to have a vehicle insurance, with vehicle that's less than one year 66% of those are insured , vehicle that's older than one year but less than 2 years are 33% insured, while less than one percent of vehicle that's older than 2 years are insured. This should explain why customer who owns a newer vehicle are less likely to be intersted with insurance promotion, because they probably alredy have one.

Customers who never had vehicle damaged only 0.5 % of those customers are intersted with vehicle insurance, 87% of customers who never had any vehicle damaged already have a vehicle insurance.

