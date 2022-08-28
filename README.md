# Assigment-1
Assignment 1 module 1
# Kickstarting with Excel

## Overview of Project
Louise is looking for information related to the success of plays. When would be the best launch date and which goal she should strive for.
### Purpose
The purpose of this analysis is to provide Louis with information related to the launch dates and funding goals of plays, so she can decide on the best launch date and the most optimal goal so that her play can be successful.
## Analysis and Challenges
This analysis provides the necessary information regarding the success rate of plays regarding launch dates and goal funding targets. The analysis can be found in [Kickstarter_Challenge.xlsx](https://github.com/kiwidata/Assigment-1/files/9440624/Kickstarter_Challenge.xlsx)
### Analysis of Outcomes Based on Launch Date
The analysis of outcomes based on launch date was performed using a pivot table and a line chart that deviated from such pivot table. The Pivot table was created using the  "outcomes","Parent category", "Year", and "Date created conversion" from the data set. A line chart was then created that showed each month of the year,throughout past years, the launch date of theaters. It showed how many were successful, failed, and were cancelled during each month.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111706055/187095679-b70e1167-8d9f-4de1-934f-99c111d71b73.png)

### Analysis of Outcomes Based on Goals
The analysis of outcomes based on goals was performed using the countifs function `CountIFS()` in excel to count how many plays were successful, fails, or were canceled based on the range of the goal. The sum of the count of projects `SUM()`, based on the range of the goal, was then calculated, which in turn led to the caculation of the percentage of the success rate by goal range. This was done by dividing the number of successful, failed, canceled projects with the total number of projects for the different goal range. The excel file provides the necessary information regarding the entire analysis [Kickstarter_Challenge.xlsx](https://github.com/kiwidata/Assigment-1/files/9440624/Kickstarter_Challenge.xlsx)
### Challenges and Difficulties Encountered
The main challenge in this analyis was using the `CountIF` function. There was a different formula for each goal range and each outcome category. This was overcome by copy and pasting the formula to all the cells, using the excel function to show the entire formula in the worksheet for all cells, and finally using the replace function to be able change the wording from the formulas at a relatively fast pace.
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Two conclusion that can be made are the following
1) the theater rate of success is much higher in May. More than twice the chance of success than failures. 
2) The theater rate of failures is very constant throughout the year ranging from 31 to 52. However based on the number of projects, and ratio between successful and fail theaters, December rate of failure is the highest througout the year.

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/111706055/187095679-b70e1167-8d9f-4de1-934f-99c111d71b73.png)

- What can you conclude about the Outcomes based on Goals?

Regarding the Outcomes based on Goals, I can conclude that the rate of failure for plays increased as the goal range gets larger. There is an exception from the 35000-45000 goal range, however this does not change the overall trend of the increased rate of failure as the goal range increase.

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/111706055/187095678-f3005924-5d72-4cd4-816d-635d3046a95d.png)

- What are some limitations of this dataset?
The limitations of the dataset includes the following, but are not limited too:
1) the amount of data for projects with of a goal of less than 20000 is relatively small. This might lead to wrong conclusions especially that the goal range is heavily screwed toward the "less than 20000" range. 
2) The data is largely screwed toward the US audience. More data points from other countries might be required to create proper conclusions for other regions.
- What are some other possible tables and/or graphs that we could create?
Other possible tables/graph:
1) Outcomes based on Launch Date - The ratio between Successful and Failed project can be calculated and graph leading to the actual percentage of success for theater lauch dates.
2) Outcomes based on Goals - A histogram chart could have been created to show the heavy screw toward goals with less than 20000. This might lead to more data been required for goal range projects of more than 20000.


