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
  - Identify product categories, product type and product detail with the highest revenue generation
  - Identify month with highest revenue generation
  - Calculate which time of the day (Morning, Afternoon, Evening or Night) has the highest transactions
  - Calculate how much was sold each month 

  ### Results
=
   From the following Analysis, I discovered :

  - Total Revenue = $699,000 , Total Transactions = 149,000 & Total Quantity Sold is 214,000
  - When filtered, 
  - Product category that generated the highest revenue is "Coffee"
  - Product type that generated the highest revenue is "Barista Espresso"
  - Product detail that has the highest revenue is "Dark Chocolate Lg", in 2/3 Locations
  - June with a total of $166,000, had the highest revenue generation
  - Hell's Kitchen which is a 1/3 of the locations generated the most revenue
  - Mornings account for about 60% of all transactions (90,000 of 149,000)
 
  ### Recommendation

 - Optimize operations for the morning rush. Since about 60% of transactions happen in the morning, schedule peak staffing and complete restocking before the morning rush begins and implement a grab-and-go flow for top items
 - Coffee and Barista Espresso drive the most revenue, so keep them consistently stocked and mainatain strict quality control
 - Audit what makes hell's Kitchen outperform the other two locations and use successful sales approach in the remaining locations.
 - Further Analysis should be carried out to understand underlying drivers : why lower sells are lagging behind, traffic by location and hour, etc
  
  ### Limitation
  
 - The dataset does not cover a full year for all periods, making Year on Year (YoY) comparisons less reliable.
 - The data has no costs, so revenue isn’t profit.

 
    
  
  
    
    
