# kickstarter-analysis

Click here to view the analysis file: [Kickstarter_Analysis](https://github.com/jzaragoza21/kickstarter-analysis/blob/main/Kickstarter_Analysis_.xlsx)

## Overview of Project & Purpose

The first module's challenge set out to further test our skills with Excel, particularly with PivotTables, COUNTIFs, percentages and visualizing data with charts. The Challenge establishes two different objectives in which we utilize the aforementioned excel skills, among many others. The first objective was to organize Kickstarter data and analyze whether there were any relationships or trends between successful, failed and canceled Kickstarter campaigns for Theater shows and the month their campaigns launched. The second objective was to analyze fundraising goal data of successful, failed and canceled Kickstarter Play campaigns. Furthermore, we were to identify whether there is any relationship between the amount of the fundraising campaign goals and its success or failure.   

## Challenges and Difficulties Encountered

In the first deliverable, the only difficulty I encountered was brief: filtering the rows to months from years in the PivotTable. Initially, I dragged the "years" field to "filters" but we needed the table to reflect outcomes by months. The difficulty was that there was no "month" field and it didn't work by right-clicking on the "row labels" and "grouping/ungrouping" the "years" either. After 30 minutes of troubleshooting, I thought to drag the "Date Created Conversion" field over to "rows." However, I still had to "ungroup" the years to only months, which ultimately solved my problem. 

In the second deliverable, it was similar in that the difficulty I encountered was brief. After I calculated my percentages of successful, failed and canceled campaigns and tried to change their number format to "percentage," it resulted in percentages showing in the thousandths position. After troubleshooting and consulting with my colleagues, I found that I needlessly added "*100" to my percentage formula in excel. All I had to do was remove the "*100" from this formula =SUM(B2/E2*100) and it resulted in percentages moving to the correct position in tenths.      

## Results

### What are two conclusions you can draw about the Outcomes based on Launch Date? 


![Theater_Launch](https://github.com/jzaragoza21/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)


First and foremost, the data clearly shows that Kickstarter campaigns that launched in May, June and July had the highest number of total successful campaigns. Specifically, May had the most with 111 total successful campaigns and June, coming in right behind May, with 100 total successful campaigns. Having said that, May, June, July and October similarly had the highest number of total failed Kickstarter campaigns. But if you look further into the data, it also shows that this is a product May, June and July being the months that launch the most Kickstarter campaigns. However, if you look at the line graph separation between those months of successful and failed campaigns, it's clear May, June and July are the best months to launch a Kickstarter campaign, on a percentage basis alone. On another note, the data also demonstrates that December is the worst month to launch a Kickstarter project with 37 and 35 total successful and failed campaigns respectively. The data and graph shows you likely have a 50 percent chance of your campaign failing if you launch in December, which could be a product of launching a fundraising effort during the holiday season and therefore having trouble generating donations. 

### What can you conclude about the Outcomes based on Goals?


![Outcomes_goals](https://github.com/jzaragoza21/kickstarter-analysis/blob/main/Outcomes_vs_Goals.png)


The outcomes based on goals data and graph shows that your Kickstarter campaign is likely to have a higher success rate if you set your campaign goals at $4,999 or less. The campaign goals of less than $1,000 and between $1,000 and $4,999 had the success rate of 76 and 73 percent respectively. These two goals also had the highest sample of total Kickstarter projects of 186 and 534 respectively. The campaign goals of $35,000-$39,999 and $40,000-$44,999 also had high success rates of 67 percent. However, the total projects of both those goals is 3 and 6, which is too small of a sample to draw a conclusion on whether there iss a relationship between those goal numbers and the project's success rate.

### What are some limitations of this dataset?

The first glaring limitation for the Outcomes based on Goals dataset is that 75 percent of the 12 goals parameters have an insufficient sample size to draw any conclusions, trends and/or relationships. 

Similarly, this could be the case for the Outcomes vs Launch Date as well. As a result, both sets allow us to extrapolate whether there are some correlations but there is not sufficient data to tell us if there is causation between Outcomes/Launch Date and Outcomes/Goals.

## What are some other possible tables and/or graphs that we could create?

The stacked column graph would have also been suitable for our objective with Outcomes based on Goals Deliverable. I'm certain I could have achieved the analysis and conclusions using the stacked column as well. 

As for tables, I think creating a PivotTable based on Parent Category and/or Subcategory and Outcomes would have been interesting to analyze. In particular, what categories of Kickstarter projects have the highest success rates.
