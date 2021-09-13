# Election_Analysis

##Overview of Election Audit: 

In order to determine the result of this election and gather relative information, we performed this election audit analysis. We extracted a complete list of candidates who received votes and the counties that particapated in the election. We calculated the total vote numbers, the number and the percentage of votes each candidate and each county received. With all the information gathered, the winner of the election based on vote number and the county with the highest turnout.

##Election-Audit Results: 

- A total of 369,771 votes were received
- The percentage of total votes and the numnber of votes for each of the three ***counties*** were as follows:
	- Jefferson: 10.51% (38855)
	- Denver: 82.78% (306055)
	- Arapahoe: 6.71% (24801)
- Denver county had the largest number of votes.
- The percentage of total votes and the numnber of votes each ***candidate*** received were as follows:
	- Charles Casper Stockham: 23.0% (85,213)
	- Diana DeGette:  (272,892)
	- Raymon Anthony Doane: 3.1% (11,606)
- The winner of the election is Diana DeGette, who received 272,892 votes and 73.8% of the total votes.

##Election-Audit Summary: 
In this analysis, we did not specify the name of any candidates or counties. Instead, the list was created in a for loop by iterating through the rows and referencing use index. Next, the votes for each categories were counted in the if statement. The benefit of this is that it's flexible in adapting to any modifications for anay election. 

For example, if more data were collected from other counties, the code can continue to include this information without changes. If other information, like cities, were collected in a separate column, or the information regarding to the name of candidates and counties were in different columns compare to our original data, the code can be expanded or fixed without major changes (index change).

Thus, this script can be easily modified and used for other elections.