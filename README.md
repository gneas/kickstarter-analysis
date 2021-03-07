# Kickstarting with Excel

## Overview of Project

The overall Kickstarter project was to help someone named Louise start a crowdfunding campaign to fund her play Fever.

### Purpose

The purpose of this analysis was to examine how different theater campaigns performed in relation to their launch dates and funding goals.

## Analysis and Challenges

I began this analysis by utilizing a dataset comprised of various different types of crowdfunded campaigns spanning the years 2010-2017. Being that the focus of this analysis centered around theater campaigns, it was necessary to filter the overall dataset accordingly. After converting the Unix timestamps to dates I was able to establish the year for each record. I then pivoted the data with it filtered on the theater campaigns broken out by their outcomes (successful, failed, canceled). Next, I created a chart (1st below) from the pivot in order to easily visualize the theater campaign outcomes in relation to their launch dates. Then, I proceeded to focus on the theater plays outcomes based on their goals. This required counting all of play outcomes based on their goal, but organizing them into manageable ranges. Once that step was completed I then created a chart designed to represent visually the all of the play outcomes based on their goals (2nd below).

### Analysis of Outcomes Based on Launch Date
![Theater Outcomes vs Launch](/Resources/Theater_Outcomes_vs_Launch.png "Theater Outcomes vs Launch")
### Analysis of Outcomes Based on Goals
![Outcomes vs Goals](/Resources/Outcomes_vs_Goals.png "Outcomes vs Goals")
### Challenges and Difficulties Encountered

One potential challenge within this process could have resulted when the theater outcomes were pivoted. It was important to be able to organize everything all based on the month. This was important because when charting against it, the monthly orgazined data would be reflected in a way that would allow for the determination of whether or not there was seasonality. Another potential challenge was organizing the data into manageable ranges. This required a COUNTIFS function that needed these goal ranges specified. This step was important because it was necessary to visualize the outcomes based on goal amounts in a clear and concise manner.

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?  
  
One conclusion is that the months of May, June, and July have been the most successful months in which to conduct a theater kickstarter campaign. A second conclusion is that when the successful data is taken in conjuction with the failed data, we can see that July isn't as successful as May or June are.
- What can you conclude about the Outcomes based on Goals?

- What are some limitations of this dataset?

- What are some other possible tables and/or graphs that we could create?

