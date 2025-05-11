# Cake-Pop-Sales-Analysis

This project analyzes A local cake pop business and their sales transaction data. The data and business analysis performed during this project explores various ways on how the local cake pop business can increase product sales/custom sales? Data visualizations were created using SQL through BigQuery and Data Visualization through Tableau Public. 

## Table of Contents
+ [Requirements](#requirements)
+ [Background](#background)
+ [Findings](#findings)
+ [Data](#data)
+ [Acknowledgement](#Acknowledgement)


## Requirements
To run queries in this project you will need the following for your machine.

-BigQuery - Google

-Data Visualization -Tableau Public

## Background

The local cake pop business started as an independent in-house bakery 2018. In October of 2022, the local cake pop business opened its first physical location. The business started off with a fixed price for each cake pop but later began to offer promotional deals. The cake pop business had six main menu items, and one specialty item per month. For the month of 3/28-4/28/23, they produced an average of fifty batches of cake pops (CPs). Fifty batches of CPs are around six hundred cake pops a month. For the month of 3/28-4/28/23 they earned $5,184.25 in cake pop sales compared to $13,000 in December 2022. The total average cost of expenses per month, documented in a Budget Report was $678.53 and $2,000 booth rent.  This leaves Stakeholders with only about $2,500 to split 50/50, for one month. Although the local cake pop business garnered customers, they did not completely understand the importance of their sales data. 

## Findings
1. Original data sourced from square sales data underwent analyzation and cleaning. First three months of sales did not track flavor variations. The fourth month tracked 1 flavor per purchase. On the fifth month I implemented a flavor tracking system at the Point-of-Sale to affectively track all cake pops in each purchase for in-store and custom sale purchases. During this period of additional data collection from March to May the new data was monitored, cleaned and transfered to a new dataset.
2. Additional tables were created including salesTrans, specialtyFlavor, weatherData, mainFlavors and totalSales with occurence_id as the primary key to link all of the tables together. Each table consist of data from square sales summary reports and national weather service reports.
3. New data collected on cake pop weight showed a major variation in product size. A proposal to collect data on each cake pop weight was made to encourage consistency. 
4. Item listing records from original sales summary contained incorrect price records, throughout the analysis the faulty data was removed, monitored or corrected over the duration of the collection period.
5. Data revealed that there was a significant decrease in sales during the months of March-September and the least popular days for sales were Monday and Tuesday.
6. Sale activity decreased between the times of 12:00-1:00 PM and 6:00 PM to 8:00 PM.
7. Other patterns in data included, sales on Lemon and Strawberry CPs were found to be the least popular. While Chocolate and Funfetti CPs were found to be the most profitable providing 50% of Net Sales Monthly. Bar graphs were produced from salesTrans data using Tableau public and BigQuery to illustrate this.
8. The following documents were delivered to stakeholders after the Data visualization presentation with detailed results of the analysis: Meeting Agendas,  Data Document, Activity Log, Marketing Analysis and Campaigns, Email Marketing Information Document, Scope of Work, and copies of Data Visualizations.

## Data 

## Data Visualizations: 

SQL Queries: [here](https://github.com/Aunestly/Cake-Pop-Sales-Analysis/blob/main/CPSAqueries) for data visualizations below.
![data viz](https://github.com/Aunestly/Cake-Pop-Sales-Analysis/blob/main/images/Dashboard1.png)

![data viz](https://github.com/Aunestly/Cake-Pop-Sales-Analysis/blob/main/images/Dashboard2.png)
temp dataset: [here](https://www.kaggle.com/datasets/aunestly/tempmainflavors?select=mainFlavors.csv)

![data viz](https://github.com/Aunestly/Cake-Pop-Sales-Analysis/blob/main/images/zerosales.png)

## Acknowledgement
The source data used in this project was generated from the local cake pops Square app monthly sales data reports. The relevant data was extracted, transfered and loaded into a new dataset. Weather data sourced from the National Weathers Service Reports and [Localconditions.com](https://www.localconditions.com/weather-kenwood-ohio/oh334/past.php).

