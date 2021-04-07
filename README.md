# Superstore_Sales_Analysis
Assumptions Made :               
- Selected a Random Date as Reference for MTD, QTD, YTD and YoY calculation since the max date on the dataset is 12/30/2018.
- The Date selection is a parameter control on the '2018 Sales Analysis' Dashboard and may be set to a different date.

 **2018 Sales Analysis** : 
  This Dashboard provides :
      - MTD, YTD, QTD and YoY Sales (Comparison between this year (2018) and Previous Year (2017)
      
      - KPIs are all interactive over Region, Category, SubCategory and Segment. 
        [The Sub-Category Filter is set to only show Relevant Values based on other filters as I figured a customer would first select the Category and we can limit the sub-   category list]
      -Top N Customers and Top N and Bottom N products per Profits Generated - These are also interactive over Region, Category, SubCategory and Segment. [These charts show data   for 2018 only, since I thought it would make sense to limit analysis to the current year in this scenario).
      -I used context filters for the interactivity for Top N filters because of Tableau Filter Hierarchy.
      
 **Historical Sales Story US** : 
 This dashboard contains the interactive Tableau Map Animation that shows how sales have grown since the first order in the dataset.
 
    - I have also added KPIs on top of the screen that show the increase in customers served, sales and units sold over the years. 
    - I used LOD expressions to be able to calculate a running total progression for the Customers Served animation.

      You may notice in the worksheets (Year to Year filter) that this solution can be scaled to do a more detailed historical analysis and see performance over the past 2 and 3 years also.

