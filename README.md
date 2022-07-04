# Kickstarting with Excel

## Overview of Project

### Purpose
Louise, a hopeful playwright, is looking for insight about what makes Kickstarter campaigns successful and unsuccessful. From the initial crowdfunding data provided, we were able to sort and filter the data down to what would be most applicable to Louise. After looking at the data from several angles that would satisfy Louise's needs, we were able to provide useful analysis based on a variety of key factors. The purpose of this analysis is to gain an understanding of factors that contribute to a Kickstarter campaign's success or failure. More importantly, the purpose of this analyisis is to provide Louise with a clear understanding of what she needs to do in order to maximiize the potential of her Kickstarter campaign so that her play is fully funded. The two factors that she is most interested in are fundraising goals and launch dates so dove into the outcomes of campaigns for plays based on those two factors.

## Analysis and Challenges

### Analysis of Outcomes Based on Launch Date
To determine the outcome of theater campaigns based on their launch date, we looked at the relationship between the dates that the campaigns were created with the campaigns that were successful, failed, and cancelled. 
![Theater_Outcomes_vs_Launch](path/to/Theater_Outcomes_vs_Launch.png)
May was the most successful month for the relevant Kickstarter campaigns while June and July were the second and third most successful. Based on this connection, spring and summer are the best times to start a theater campaign. The numbers for the unsuccessful campaigns were consistent through the entire year with May, July, and October being the most unsuccessful. Since the number of failed theather campaigns were fairly consistent despite the month, there is likely a different factor contributing to their failure. 
### Analysis of Outcomes Based on Goals
To deteermine the outcome of play camapaigns based on their fundraising goal, we looked at the number of campaigns that were successful within 12 ranges. After gathering the total number of successful, failed, and cancelled campaigns withiin those ranges, we took the percentage of those totals and displayed them in a line graph. 
![Outcomes_vs_Goals](path/to/Outcomes_vs_Goals.png)
51% of the total projects had a fundraising goal between $1,000 and $4,999. The greatest total of successful campaigns (388) and unsuccessful campaigns (146) had fundraising goals in that range. Based on that connection, there is another factor that is contributing to the outcomes. 
### Challenges and Difficulties Encountered
There were a few difficulties with getting an accurate count of the number of successful, failed, and cancelled campaigns based on their fundraising goals from the Kickstarter sheet in the excel file. That difficulty was overcome by copying the filtered results for each outcome and adding them to individual sheets to call the data from. The next difficulty was sorting the row labels in ascending order for the "Outcomes Based on Goal" PivotChart because "Less than 1000" and "5000 to 9999" were at the bottom of the table and the end of the x-axis. This difficulty was overcome by right clicking those row labels then manually moving them to the top of the table. 
## Results
Based on the analysis of the Theather Outcomes by Launch Date, the most succesful months to start a campaign are May through July. The failed campaigns were relatively unaffected by the month so there is another factor contributing to their failure. 
Play campaigns with huge fundraising goals were unsuccessful for the most when looking at the totals of the campaigns within the different ranges of goals. The majority of the campaigns had a goal between $1,000 and $4,999 with a 73% success rate. Based on those numbers, there is a different factor contributing to the failure of campaigns in that category. To give the analysis of the Outcomes by Goals more context, adding a graph with the total projects based on their fundraising goal would help. ![Outcomes_vs_Goals_Count](path/to/Outcomes_vs_Goals_Count.png) With the size of the dataset and the range of its variables, the dataset is more robust than limited. 
