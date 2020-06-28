# Kickstarting with Excel

## Overview of Project

### Purpose
Performing analysis on Kickstarter data to uncover trends in terms of how different campaigns fared in relation to their launch dates and their funding goals.

### Background
Louise’s play Fever came close to its fundraising goal in a short amount of time. Now, she wants to know how different campaigns fared in relation to their launch dates and their funding goals. Using the Kickstarter dataset, we will visualize campaign outcomes based on the theater launch dates and the funding goals for plays to uncover trends in various campaigns.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
Firstly, we generated a pivot table and applying filters for theater. We can see that the total number of successful, failed and canceled theater campaigns is 1,369.
We then generated a Pivot Chart with line graph and using filters to help us determine trends in theater outcomes based on launch date. We can see by looking at our new chart that the month of May has the greatest success rate. There are higher numbers of success than failure for all months in the year.

![Theater_Outcomes_vs_Launch](https://github.com/grwon/kickstarter_challenge/tree/master/resources/Theater_Outcomes_vs_Launch.png).

### Analysis of Outcomes Based on Goals

We populated the number of successful, failed and canceled play project campaigns in tabluar data format. We noted that most of the play campaigns have goals less than $10,000 and projects with goals under $5,000 have the highest success rate. There were no canceled projects.

![Outcomes_vs_Goals](https://github.com/grwon/kickstarter_challenge/tree/master/resources/Outcomes_vs_Goals.png).


### Challenges and Difficulties Encountered

One of the possible challenges we could encounter is errors in our data analysis. We could encounter #DIV/0! error and we would have to go through debugging process to investigate and resolve the error. Supposed we have #DIV/0! error in Percentage Successful column, we would have to investigate and check the formula, it is possible that we have a typo in the formula where it's dividing the Number Successful by Number Canceled instead of Total Projects. This can be correct by changing the formula to divide Number Successful by Total Projects in Cell F2 and double click bottom right of Cell F2 to fill the corrected formulas for the entire Percentage Successful column.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
We have identified the overall trends in the theater category with our Theater Outcomes based on Launch Date chart. We can conclude that theater campaigns are successful overall as the successful line is above failed line for all the months in a year. This means the number of successful outcomes exceed failed outcomes throughout the year. The line chart shows a spike that began in May and June, but that tapers off by the end of the year. Therefore, May and June are the most successful months to launch Kickstarter campaigns. In contrast, December is not the best time of the year to launch a theater campaign.

- What can you conclude about the Outcomes based on Goals?
Most of the project goals for plays are between $1,000 to $5,000 and projects with goals under $5,000 have the highest success rate. Therefore, Louise should set the budget for future play projects for less than $5,000 in order to increase chances of success to reach funding goals.

- What are some limitations of this dataset?
This dataset has not consider the type of theater plays that backers prefer. There could be a current trend and preference for a specific genre that helps to explain the rate of success for play campaigns. Age of backers are not considered in this dataset, the age of backers could explain interest in supporting play campaigns versus other categories.

- What are some other possible tables and/or graphs that we could create?
We could look at theater outcomes based on duration of campaigns. We could analyze the pivot chart with line graph to see if there are any trends to link highest success rate  with the length of campaign. We could create a pivot table with country as rows, filtered by Subcategory with plays and values with Count of outcomes to uncover which countries have the most successful play campaigns. We could generate pivot chart with stacked column format to visualize which countries have the most successful vs failed play campaigns.
