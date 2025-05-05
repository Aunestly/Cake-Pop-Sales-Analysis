# Cake-Pop-Sales-Analysis

# SQL Data Analysis Project

This project analyzes A local cake pop business and their sales transaction data. The data and business analysis performed during this project explores various ways on how the local cake pop business can increase product sales/custom sales? Data visualizations were created using SQL through BigQuery and Data Visualization through Tableau Public. 

## Table of Contents
+ [Requirements](#requirements)
+ [Background](#background)
+ [Findings](#findings)
+ [How to Use](#how-to-use)
+ [Acknowledgement](#acknowledgment)
+ [Contribution](#contribution)

## Requirements
To run queries in this project you will need the following for your machine.
-BigQuery - Google
-Data Visualization -Tableau Public

## Background
Background: 

The local cake pop business started as an independent in-house bakery 2018. In October of 2022, the local cake pop business opened its first physical location. The business started off with a fixed price for each cake pop but later began to offer promotional deals. The cake pop business has six main menu items, and one specialty item per month. For the month of 3/28-4/28/23, they produced an average of fifty batches of cake pops (CPs). Fifty batches of CPs are around six hundred cake pops a month. For the month of 3/28-4/28/23 they earned $5,184.25 in cake pop sales compared to $13,000 in December 2022. Total average cost of expenses per month, located in the Budget Report is $678.53 and $2,000 booth rent.  This leaves Stakeholders with only about $2,500 to split 50/50, for one month. Although the local cake pop business garnered loyal customers, they did not completely understand the importance of their sales data. 

## Findings
1. Original data sourced from square sales data, cleaned and analyzed. First three months of sales did not track flavor variations. The fourth month only tracked 1 flavor per purchase. A flavor tracking method was added at the Point of Sale to properly track all cake pops during in-store and custom purchases. During this period of additional data collection from March to May the new data was collected, monitored, cleaned and transfered to a new dataset.
2. Additional tables were created including salesTrans, specialtyFlavor, weatherData, mainFlavors and totalSales with occurence_id as the primary key to link all of the tables together. Each table consist of data from square sales summary reports and national weather service reports.
3. A proposal to collect data on each cake pop weight was made to encourage consistency. New data collected on cake pop weight showed a major variation in product size.
4. Item listing records from original sales summary contained incorrect price records, throughout the analysis the data was monitored and corrected overtime.
5. Data showed that their was a significant decrease in sales during the months of march-september and the least popular days for sales were Monday and Tuesday.
6. Sale activity decreased between the times of 12:00-1:00 PM and 6:00 PM to 8:00 PM.
7. The sales on Lemon were the lowest, with Strawberry not far behind.

