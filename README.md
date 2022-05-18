# Kickstarter-analysis

# Kickstarting with Excel

## Overview of Project

* Use an Excel spreadsheet of several thousand crowdfunding projects to compare campaign outcomes based on            launch dates and their funding goals.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date

* Analysis was performed with the use of a pivot table to filter date, category and outcomes of the projects. The table depicts each months successful, failed and canceled plays. The table also shows the Grand total of plays for each month, as well as the Grand Total for each outcome.

* A line chart was created to visualize the relationship between outcome and launch month. 

* <img width="1440" alt="Screen Shot 2022-05-17 at 2 36 35 PM" src="https://user-images.githubusercontent.com/105119531/168886731-ac96cc92-1410-45e2-be97-5ab1910b55fa.png">


### Analysis of Outcomes Based on Goals

* An Outcomes Based on Goals sheet was created containing columns for:
  * Goal
  * Number of Successful
  * Number of Failed
  * Number of Canceled
  * Total Projects
  * Percentage Successful
  * Percentage Failed
  * Percentage Canceled

* Rows for the sheet contained Goal amounts listed as:
  * Less Than 1000
  * 1000 to 4999
  * 5000 to 9999
  * 10000 to 14999
  * 15000 to 19999
  * 20000 to 24999
  * 25000 to 29999
  * 30000 to 34999
  * 35000 to 39999
  * 40000 to 44999
  * 45000 to 49999
  * 50000 or More
 
 * COUNTIFS() function was applied to populate the Number of Successful, Failed and Canceled columns by filtering     the outcome, goal and Subcategory column to "plays". 
 
 * The Sum() function was applied to the Total Projects Columns giving a total for each outcome.
 
 * Percentages were determined for each Outcome based on the goal ranges listed.

 * A line chart was created to visualize the relationship between goal-amount ranges and percentage of successful,     failed and canceled projects

*<img width="1440" alt="Screen Shot 2022-05-17 at 2 36 09 PM" src="https://user-images.githubusercontent.com/105119531/168886817-10163aeb-4e69-4184-a1d3-f31af773357a.png">


### Challenges and Difficulties Encountered

* The main challenge I encountered during the Outcomes Based on Launch Date analysis was correctly identifying       which categories needed to go into the correct field in creating the pivot table.

* The Difficulties I encountered during the Outcomes based on Goals analysis were, filtering the data          appropriately in the function rather than filtering the data in the Kickstarter sheet.  I also had issues with     errors in my functions that discovered after creating the line chart. 

## Results

- Two conclusions that can be made from the Theater Outcomes by launch date are:
 
 * The results showed May, June and July had a significantly higher rate of successful campaigns than other          months.
  
  * There did not seem to be any significant variations for failed campaigns over the course of the year. There       were almost no canceled campaigns to begin with, resulting in no significant conclusions.

- I can conclude the Outcomes based on Goal analysis shows a trend for percentage of successful campaigns to          decrease as the goal amount increases and the percentage of failed campaigns to increase as the goal increases. 

- Limitations of this dataset would include greater economic considerations during the dates of the campaigns and   social reach of the organizers of each campaign.

- Some other possible tables and/or graphs that I could create would be graph showing the rate of growth in         pledges compared to the total length of the campaign for various categories and subcategories. I could also       show table comparing the percentage of successful, failed and canceled campaigns for each country.
