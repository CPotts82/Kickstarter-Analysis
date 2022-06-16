# Kickstarter Analysis 
## Campaign Analysis of Launch Dates and Funding Goals
### Overview
The Kickstarter data analyzed is composed of over 4000 crowdfunding camapaigns that took place from October 2010 to March 2017. These campaigns were across multiple countries with a multitude of different categories. The objective of this analysis is to assist a new playwrite in researching crowdfunding campaigns to gain insight for launching her own future campaign(s). Our focus was on theater and specifically "plays".  We examined the launch dates and funding goals and compared them to the outcomes - "successful, failed and canceled". This analysis focused on how these theater crowdfunding campaigns performed with respect to the launch dates and funding goals. 

### Analysis
#### Launch Dates
The first focus of this analysis was on the launch dates of theatatrical plays.  I filtered the parent category and years out of the kickstarter data and created a pivot table. In the pivot table, years were araranged to to reflect each month and only focused on the outcomes - "successful, failed and canceled".  The "live' outcome was eliminated.  The Parent category was filtered to only reflect data for "theater". After the pivot table was created, then a line chart was created to reflect this specific information. You will see the dramatic peak in the months of May and June that show they are the most successful months for launching a theater crowdfunding campaign. You will also see that the months of January, March and September were the least successful months.  The end of the year starting with October and going through December shows a steady decrease in successful campaigns.  The amount of failed campaigns stayed in the 20 to 55 range for each month of the year. 
![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/106348899/174135983-32934346-b771-4803-ba8c-f4ad03c7277c.png)

#### Funding Goals
The second focus of this analysis was on funding goals of theatrical campaigns.  The data targeted here were the goals for each campaign - these goals were placed in twelve different ranges from 0 to 50,000+.  Along with the goals, other data targeted were the outcomes - "successful, failed and canceled" which were evaluated to find the percentage of each outcome based on total number of projects within each goal range. With this information a line graph was created to illustrate percentages of outcomes (successful, failed and canceled) compared to funding goals.  You will see that the highest percentages of successful campaigns were in the less than 1000 to 5000 range (almost 80%) as well as in the 35,000 to 45,000 range (alsmost 70%) . The percentage of failed campaigns rose fairly steadily from 0 to 25,000 range, decreased from 25,000 to 35,000 and then peaked at 45,000 to 49,999.   
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/106348899/174139499-02729bff-e7c2-4e3a-8ab1-812475730b6c.png)
Challenges that were encountered while analyzing the funding goal data was the use of Countifs formulas in the number of successful, failed and canceled columns.  These Countifs formulas were unfamiliar to me and had to be exact.  I was able to figure out not only how to use them in this data set but also how to use 3 different sets of criteria in them.  I was able to figure out the main formula with the goal ranges and then just adjust each formula for the corresponing column - changing the outcome for each column. 

### Conclusions

#### Recommendations - Theater Outcomes By Launch Dates
My recommendation based on the findings from the Theater Outcomes by Launch Date is to launch a theatrical crowdfunding campaign in May or June.  To be more specific I would recommend a launch date for the new campaign to be mid-May, May 15th and then run for about a month until mid-June.  My second recommendation (if a May or June launch date is not manageable) is to avoid the holiday season.  Avoid launching and running any campaign between the months of October and January.  

#### Recommendations - Outcomes Based on Goals
My recommendation for setting goals for the campaign is to set a goal of $1000 or less (as this was the most successful goal range) or to set a goal of $35,000 to $45,000 (as this was the second most successful range). Avoid setting goals above $45,000 - these are the least successful.

#### Limitations
One of the limitations in this data set is that we did not take in to account the countries that these campaigns happened in.  From past analyses this can be very important information.  The economies of the countries will definitely factor in to the Outcomes based on Goals analysis.  We could have analyzed this data and created a chart with the outcome percentages vs goal ranges and then filtered by country.  

Another limitation is that this analysis did not include the length of time the campaigns ran for.  This is very pertinent information that should be taken into account when looking at launch dates.  Maybe is was not so much the launch date that caused a campaign to be unsuccessful bu the length of time the campaign went for, either too short or too long.  An Outcome vs. length of campaign chart could have been created to reflect this data.
