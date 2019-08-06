
![image](https://user-images.githubusercontent.com/43391446/62583821-d6772280-b87f-11e9-8890-a8e8ab795ee1.png)

Housing Rent Prices for 2-bedroom apartments in the major Canadian Cities
Susiette Adams, Student ID 303594
 Sprint 1
 
Abstract

This project was assigned by York University 1050 Advanced Analytics Capstone Course. The goal for this project is to find insights from the housing rental market using various analytical tools. This information will provide a better understanding of what drives rent cost. The focus will be to find fact-based insights on meaningful patterns in the housing market.

The boundaries of this project:

Upon completion the results will outline the cities that are most livable / cost effective for renter’s base on the locations.
Evaluating factors such as household income and market indicators will be used to determine if there are correlations between the costs of the housing in the top Canadian cities.
Completion of this project will be by August 27th 2019.

Research questions

What are the top 10 cities with the highest and lowest average income?
What cities have the highest and lowest rent cost?
What are the Market Indicators that affects rents cost in these cities?

What is needed to be done to run the codes?

Python programming language was used to do perform the analysis. To be able to run the codes and see the outputs you will need to have Python installed on your computer. All libraries that is needed to run the codes have been inputted within the codes. You would also need to download the 3 datasets from the Data folder and set the directory to were you save the files on your computer.

Data source

The datasets were gathered from third-party external source from the Canadian Mortgage and Housing Corporation website. The data sets include Average Income After Tax Renters, Average Rent 2 Bedrooms, Housing market Indicators.

https://www.cmhc-schl.gc.ca/en/data-and-research/data-tables/real-average-after-tax-household-income-renter-households

https://www.cmhc-schl.gc.ca/en/data-and-research/data-tables/average-rent-2-bedroom-apartments-canada-provinces-cmas

https://www.cmhc-schl.gc.ca/en/data-and-research/data-tables/housing-market-indicators

Introduction and overall approach

Click on the hyperlink https://github.com/susietteadams/CSDA-1050F18S1/tree/master/SusietteAdams%20303594/spint%201 this will take you to the Sprint 1.py python and readme file. There were 3 data sets that was used for these analysis and the same approach was used to perform and will be used to complete the feature engineering process and the Exploratory Data Analysis. This is because the datasets contain the same type of information. The variables include the rang of the years, the market indicators and the cities. 

Observation and recommendation

Base on the exploratory analysis our research questions seems to be achievable. We will focus on utilizing all 3 data sets for the process of visualization and modeling.

Data Visualization

Below are the top 10 earning cities

![image](https://user-images.githubusercontent.com/43391446/62583384-0291a400-b87e-11e9-928b-d4747b95029f.png)

Below are the bottom 10 earning cities

![image](https://user-images.githubusercontent.com/43391446/62583423-2d7bf800-b87e-11e9-9b7c-a52e6a50b539.png)

Checking for outliers

![image](https://user-images.githubusercontent.com/43391446/62583471-61571d80-b87e-11e9-9e6c-e2387daae189.png)

Best fit distribution plot

![image](https://user-images.githubusercontent.com/43391446/62583517-8ba8db00-b87e-11e9-928e-ae26f9a7fe99.png)
![image](https://user-images.githubusercontent.com/43391446/62583530-9c595100-b87e-11e9-9f4c-fb6a79c2c015.png)

Residual Plot

![image](https://user-images.githubusercontent.com/43391446/62583540-b09d4e00-b87e-11e9-81fb-def5f1df1115.png)

Plotting the missing values

![image](https://user-images.githubusercontent.com/43391446/62583568-c3b01e00-b87e-11e9-9b28-5fd149210f09.png)

Steps to be taken

Complete the data cleanup process and assign values in the missing data for the market indicator dataset. 
Normalize and transform the skewed data
Remove outliers to prepare the datasets for modelling.
I would also like to take a closer look at the top and lower 10 results to see if there are any relation in the cities and similarities within the market indicators.