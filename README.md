# Brazil-Energy-Demand-Analysis
![](LightbuldforHomepage.jpg)

## INTRODUCTION
This is a **Power BI** project on **Analysis and Visualization on Energy Consumed in Brazil**. The derived insights is to answer crusial questions and help make data driven decisions.

_**Disclaimer**_: All the datasets and reports are fictitious and do not represent any person, institution, country or person, but a dummy dataset to demostrate my **skills** and **capabilities** on Power BI. 😃

## PROBLEM STATEMENT
To analyse and visualise
1. Find the total energy consumed 
    - For each year
    - Total for all year 

2. Find the lowest energy consumed in a month by year and the highest energy consumed in a month by year

2. Find the lowest energy consumed in a day, in a year and highest energy consumed in a day, in a year.  

## DATA QUAITY REPORT
Data quality reporting is the process I used in removing and reorganising all compromising data. 
![](DataQualityReport.JPG)

## DATA SOURCING 
The data was collect from Kaggle.com and it contains 201,312 and 2 fields

![](DatasetPQ.JPG)   

[Click here for the dataset](https://www.kaggle.com/datasets/arusouza/23-years-of-hourly-eletric-energy-demand-brazil)

## DATA TRANSFORMATION
Data cleaning and transformation was carried out using **Power BI** Query. 
1. _Data in the table are not from the same period; only a month data for 2023 was recorded in the dataset_ **###Cleaning** the one (1) month record for 2023 was removed in other not to skew the data. 
2. _The Index Column was not in the appropriate data type **Cleaning*** The Index data type was changed to date and Hourly, Number. 
3. _Inconsist decimal place_ **Cleaning** all values was rounded up to an whole number. 
4. From the index column, which contains time and date, time was extracted to a seperate column **_Time_** so to analyze the data based on time 


## DATA MODELING 
No modeling was required since its just a table 

## ANALYSIS AND VISUALIZATION
![](Energydemandproject.JPG)

Just as they say, the off-peak hours (when demand for power is at its lowest) is in the night between 10pm to 8am. This analysis proved that saying. During the analysis of this project, in no time was the off-peak hours greater than the peak hours. The peak hours is from 9am and rose up. 

Off-peak hours                                                  |                               Peak hours 
