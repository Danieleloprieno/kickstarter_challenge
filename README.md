# Crowdfunding Campaigns: How Timing and Goal Setting Impact Campaign Success

## Overview of Project

### Purpose
Crowdfunding campagins can be a vital resource for artists vying to launch their dream projects.  Planning a successful KickStarter campgain relies on many factors, with timing and goal setting being two important factors to consider.  Utilzing an international KickStarter Excel dataset with data on several thousand crowdfunding campaings, this analysis aims to understand campaign outcomes in relation to their launch dates and funding goals in order to better understand these two factors.   

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
First, we look at campagin outcomes in relation to their launch date, to better understand hte impact of campagin timing on success.  This was accomplished by creating a PivotChart to filter data by time and campaign type.  Once filtered to only display theater campagins, a table was constructed to look at outcomes (successful, failed, or canceled) across months.  This tells us how campagins started at different points of the year fared relative to others.

![Table of Theater Outcomes by Launch Date](/resources/Theater_Outcomes_by_Launch_Date_Table.png)

Then, a chart was created to illustrate the same data over time.  A line chart was selected as it is the best way to chart trends that occur over a period of time.

![Chart of Theater Outcomes by Launch Date](/resources/Theater_Outcomes_vs_Launch.png)

### Analysis of Outcomes Based on Goals
Next, an analysis of campaign outcomes relative to fundraising goal was conducted.  For this analysis, campaing category was further filtered from theater to plays specifically.  First, fundraising goals were condensed into smaller categories, ranging from less than $1000 to over $50,000.  A table was created to illustrate the frequency of each campaign outcome based on goal amount.

![Table of Play Outcomes Based on Goal](/resources/Outcomes_vs_Goal_Table.png)

Lastly, percentages of campaign outcomes in each goal category were calculated.  These percentages were charted using a line graph to better illustrate patterns as campaign goal amounts increase.

![Chart of Play Outcomes Based on Goal](/resources/Outcomes_vs_Goals.png)

### Challenges and Difficulties Encountered
I did not experience any challenges per se, but I would imagine getting hte months to populate in the PivotTable could be a stumbling block.  I did spend some time getting the first chart to change colors to match cateogires intuitively and that took me a while to figure out.  Upon discovering that canceled had dissappeared as an option initally when looking at plays alone, I thought I had erronosuly copied an incorrect version of the dataset! I downloaded a fresh copy to check and saw that the issue was just that there were no canceled play campaigns.  I've folded a discussion of that into my analysis below.  

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?

First glance at the theater outcomes data shows that most KickStarter campaigns for theater productions are successful - in fact, the ratio of successful campaings to failed ones is almost 2:1 across the board.  From the table alone we can see that this trend holds (for the most part) across all months with the except on December - plays that start their campaigns then are just as likely to fail as they are to succeed.  Perhaps this has to do with the holiday season, and patrons are less likely to contribute after just spending money on all of their Christmas presents.

The chart of theater outcomes by their lauch date tells a colorful story - successful campaigns are in green and failed ones are in red for ease of readablity.  KickStarter campagins for theater in the summer months (May - July) have the highest ratio of success to failure - indicating that the summer might be a good time to start a theater fundraising campaing.  

- What can you conclude about the Outcomes based on Goals?

We can see early on in the Outcomes based on Goals analysis how skewed the data is - in fact, by seperating out campaigns less than 1000 from those 1000 to 4999, we may have dampened the power of smaller goal play campains.  Taken together, campaigns under $5k make up well over half of all play campaigns.  Our analysis also reveals that these campaings are far more successful relative to campaings with higher goal amounts, so setting smaller, more realistic goals ($5k or less) for plays specifically seems to yiled better results.

- What are some limitations of this dataset?

Relatively few number of canceled theater productions - while not necessarily a problem per se, it does mean that once we drill down to looking at plays alone, we have no data whatsoever.  While we can certianly conduct a robust assessment of success and failed campagins with the data at hand, we don't have enough evidence to make any claims about how goal amounts or even time really impacts canceled prodcutions.  On the bright side - our data indicates that canceled campaigns are relatively rare in the theater space, and the ratio of successful to failed campaigns is nearly 2:1 in theater and plays specfically, which is good news for those raising money for new productions.  

Skew of goals data - the results presented below, especially the outcome of campaign by goals data, should be caveated with the fact that the data is heavily skewed.  The majority of all campagins is less than $5k, and over 95% of the data lives below the middle value of our constructed scale (less than $25,000).  While the line chart has drastic movement at the tail ends, it's based on fewer and fewer data points, making it less clear to interpret.  

- What are some other possible tables and/or graphs that we could create?

Based on the skew of the goals data, it might be beneficial to adjust the categories and see what, if any, new patterns are produced.  At the very least, a recalibration of categories might make a data visualization utilizing percentages more legible/easier to interpret.  As it is now, the few number of data points in goal categories $25,000 and higher alsmot make that part of the chart look misleading, as if there were great variation in outcome when really a better explanation is the smaller frequecy of occurance.  Perhaps using even 5k brackets for goals, and capping the high end of the bracket at $30,000 rather than $50,000 would be beneficial. 
