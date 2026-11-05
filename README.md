# Power BI : Coffee Sales Business Analysis 
#### Table Of Contents
- [Project Overview](project-overview)
- [Data Source](Data-source)
- [Tools](Tools)
- [Data Cleaning](Data-cleaning)
- [Data Analysis](Data-analysis)
- [Results](Results)
- [Recommendations](Recommendations)
- [Limitations](Limitations)


  ### Project Overview

  This project analyzes six months of transactional sales data from a coffee shop chain operating from three store locations.
  The goal was to generate insights that support better decision making by understanding sales activity across periods.

  ### Data Source

  This data source is a "Coffee Shop Sales.csv" file.

  ### Tools

  - Data Cleaning : SQL
  - Data Analysis & Visualization : Power BI

  ### Data Cleaning

   The dataset required some cleaning steps to ensure usability:

  - Corrected date and time field types for date/time analysis
  - Created a transaction month calculated column to extract month names from dates
  - Created time of day column to categorize transactions into Morning, Afternoon & Evening
  - Trimmed excess spaces
 
  ### Data Analysis
    
   During the Analysis, I was able to :

  - Calculate total transactions, avg order value and total quantity sold
  - Identify product categories and products revenue generation
  - identify month with highest revenue generation
  - Calculate which time of the day (Morning, Afternoon, Evening or Night) has the highest transactions
 - Calculate how much was sold each month 

  ### Results
=
   From the following Analysis, I discovered :

  - Total Revenue = $699,000 , Total Transactions = 149,000 & Total Quantity Sold is 214,000
  - Product category that generated the highest revenue is "Coffee" & least revenue is "Packaged chocolates"
  - Product type that generated the highest revenue is "Barista Espresso" & least revenue "Green Beans"
  - June with a total of $166,000, had the highest revenue generation
  - Hell's Kitchen which is a 1/3 of the location has the highest transactions.
  - Mornings account for about 60% of all transactions (90,000 of 149,000).
 
  ### Recommendation

 - Build operations around the morning rush. Since about 60% of transactions happen in the morning, make sure the busiest stores are fully staffed and stocked before it starts. 
   Prepare the top sellers in advance and set up a fast grab-and-go flow
 - Coffee and Barista Espresso drive the most revenue, so keep them always in stock and keep quality consistent
 - Test Hell's Kitchen sales approach in the other two locations 

  ### Limitation
  
 - The dataset does not cover a full year for all periods, making Year on Year (YoY) comparisons less reliable.
 - The data has no costs, so revenue isn’t profit.

 
    
  
  
    
    
