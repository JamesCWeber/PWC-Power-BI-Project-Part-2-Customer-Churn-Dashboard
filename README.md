# Customer Churn Dashboard (PWC Power BI Project Part 2)
![Introductory Picture](Customer_Churn_Pic.png)
## Introduction
This dashboard is Part 2 of a project from the [PwC Power BI micro-internship](https://www.theforage.com/simulations/pwc-ch/power-bi-cqxg) hosted by Forage. Pricewaterhouse Coopers International Limited (PwC) is a multinational professional services brand of firms that specializs in auditing and tax and business consulting.

In this task, the retention manager for PhoneNow, a fictional telecom company, has tasked me to put together a dashboard about customer retention. The purpose of creating the dashboard is to help identify which customers are at risk of churn in advance.

## Problem Statement
PhoneNow's customers are hard earned and the company does not want to lose them. The retention department's goal is to convince customers who have terminated their contract to continue business with PhoneNow. However, the retention department contact customers after they have ternimated their contract. The department wants a more proactive approach by determining which customer base are at risk of churn.

## Skills Demonstrated
* Power BI
* Data Visualization
* Dashboard Creation
* Defining KPIs
* Data Transfroming (Excel)
* Data Transforming (Power BI)

## Data Sourcing
This data was provided to me by the PwC Power BI microinternship hosted by Forage. A copy of the data is included in this repository under the file name: 02 Churn-Dataset (Cleaned).xlsx.

## Data Attributes
The data is from PhoneNow's call center. The data ranges from Jan. 1 2021 to Mar. 31 2021.
* customerID - A unique ID issued to each customer.
* gender - The customer's gender.
* SeniorCitizen - Whether or not the customer is a senior citizen.
* Partner - Whether or not the customer has a partner/spouse.
* Depndents - Whether or not the customer has any dependents.
* tenure - The length of time the customer has done business with PhoneNow.
* PhoneService - Whether or not the customer has a phone line with PhoneNow.
* MultipleLines - Whether or not the customer has more than 1 phone line with PhoneNow.
* InternetService - Whether or not the customer use PhoneNow as their internet provider.
* OnlineSecurity - Whether or not the customer is using PhoneNow's online security service.
* OnlineBackup - Whether or not the customer is using PhoneNow's online backup service.
* DeviceProtection - Whether or not the customer is using PhoneNow's device protection service.
* TechSupport - Whether or not the customer is subscribed to PhoneNow's tech support.
* StreamingTV - Whether or not the customer is using PhoneNow's TV streaming service.
* StreamingMovies - Whether or not the customer is using PhoneNow's movie streaming service.
* Contract - The type of payment contract the customer is using (monthly, yearly, etc.)
* PaperlessBilling - Whether or not the customer is receiving an electronic bill.
* PaymentMethod -  The method in which a customer pays their bill.
* MonthlyCharge - The monthly cost for the customer.
* TotalCharge - The total cost for the customer.
* numAdminTicket - The number of tickets a customer have submitted for administrative support.
* numTechTicket - The number of tickets a customer have submitted for tech support.
* Churn - Whether or not the customer has churned.

## Data Transformation
The data was cleaned and transformed using Excel and the Power Query Editor from Power BI. The steps used to clean and transform the data set are:

In Excel:
* The "SeniorCitizen" column is in binary (1 = yes, 0 = no). However, other columns such as "Partners" and "Dependents" are written in Yes No format. The "SeniorCitizen" column was converted into Yes No format to match with the rest of the columns.

In Power BI:
* 
