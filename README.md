# kickstarter-analysis_Module1Challenge
Module 1 Challenge
# Kickstarting with Excel

## Overview
This analysis was completed to show trends in kickstarter campains so the end user can make data-driven decisions and have a successful campain. There are 2 main components to the analysis: 
1. Examine Theater outcomes by lauch date.
2. Examine outcomes of Plays based on fundraising goal. 
By approaching the analysis from both outcomes and launch date we are able to uncover 2 different dimensions that will help Louise be successful in her own goals.
### Purpose
The purpose of analysing these trends  was so Louise can make a data-driven decision on how to have a successful kickstarter campain. 
## Analysis and Challenges
The first challenge in this analysis was doing quality control on the data and data cleaning. There was a lot of extra data that didn't relate to Louise's project so many of the categories were filtered out. During the data cleaning we split some columns into multiple columns so we could look at the differences between overall Theater campains and more specific Play campains. The unix timestamp had to be convereted into human readable date format, and that completed the data cleaning.
### Analysis of Outcomes Based on Launch Date
The first analysis completed was analysis of outcome based on launch date of the campain. Please see Theater Outcomes based on Lauch Date image file for the graph our the findings. the most successful lauch date are in the month of May, however anywhere in the range of April through July also yeid successful results.
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/95047485/146487463-ecd1d17a-30b5-4fcc-85dd-b287374376a8.png)

### Analysis of Outcomes Based on Goals
The second analysis was of Success rate based on monetary goal of the campain. Please see outcomes and goals image file in the references folder. There is a 76% success rate for campains with under $1000 goals. As the goals increase the success rate slowly decreases. There is a significant dip in successful campains which ask for $20,000-$35,000. At $35,000 or greater there is a little jump in success rate, however once the goals reach $45,000 the success rate takes a deep dive again.
 ![Outcomes_vs_Goals](https://user-images.githubusercontent.com/95047485/146487467-f4ec8c7c-d8fc-4ee5-bd2f-b4f4e4ce46da.png)

### Challenges and Difficulties Encountered
The most challenging aspect of this analysis was the initial data cleaning and filtering. 
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
Louise should launch her campain in the spring in order to be the most successful.
She should avoid launching a campaign in December as that is the most unsuccessful month. 
- What can you conclude about the Outcomes based on Goals?
Louise should launch with either a goal of under $25,000, or between $35,000 and $45,000 to have the most success.
- What are some limitations of this dataset?
The subcategory only goes as detailed as play. A phase 2 for this analysis might be getting a play specific dataset and see which kinds of plays have most successful outcomes. 
- What are some other possible tables and/or graphs that we could create?
We could relate average donation to outcome with a bar chart and filter by subcategory. Descriptive statistics might also be helful for this project to show Louise the another aspect between succesful and failed campains. 
