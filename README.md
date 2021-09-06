# Election Analysis Challenge
---
## Overview of Project
The Colorado Board of Elections has asked that an audit be performed of a recent congressional election using Python and Visual Studio Code editor.  The requested analysis focused specifically on three counties in Colorado. The objective was to identify the following:
- Counties 
- Candidates
- Votes per County
- Vote per Candidate, Total Votes & Percent of Total Votes Cast
- Largest County Vote Total
- Winning Candidate Based on Total Votes & Percentage of Votes Won

## Analysis of Results
### Total Votes Cast, Candidates, Counties
Utilizing [election_results.csv](https://github.com/jwolfe27/Election_Analysis_Challenge/files/7117731/election_results.csv), Python and Visual Studio Code Editor, we were easily able to identify the participating Counties, Candidates and Total Votes:

![PyPoll Code 1](https://user-images.githubusercontent.com/89044350/132258830-8271e615-5fca-4c6b-b611-79d9c381617c.PNG)

Vote Total: 369,711
### Votes Cast by County:
The below code calculates the number of votes per county, revealing the total number of votes and the percentage each county accounts for:

![PyPoll Code_County_Percent_Vote](https://user-images.githubusercontent.com/89044350/132259181-d635e265-4d29-496d-b0ae-adf1a46ca95f.PNG)

County Vote Totals
- Denver: 306,055 Votes = 82.8% of Total Votes Cast
- Jefferson: 38,855 Votes = 10.5 of Total Votes Cast
- Arapahoe: 24,801 Votes = 6.7% of Total Votes Cast

### County with Largest Number of Votes:
Denver County has by far the most votes cast totaling 306,055 making up almost 83% of the total votes cast in the election.

### Candidate Vote Totals

The below code calculates the number of votes per candidate, reveailing the total number of votes and percentage of vote each candidate accounts for:

![PyPoll Code_Candidate_Vote_Total](https://user-images.githubusercontent.com/89044350/132259831-c6d0abc3-183e-4f4a-a655-b1df442efd49.PNG)

Candidate Results:
- Diana DeGette: 272,892 Votes = 73.8% of Total Vote
- Charles Casper: 85,213 Votes = 23% of Total Vote
- Raymon Anthony Doane: 11,606 Votes = 3.1% Total Vote

Diana DeGette achieved a landslide victory winning almost 74% of the Total Votes Cast

## Proposal

Restructuring the script contained herein could prove to be extremely valuable should the Colorado Election Commission need to evaluate results from additional counties, other states or even national Presidential elections.  By simply changing the "County" list to "US States", election data on a national scale could be analyzed.  

Another way this code could be utilized is to breakdown which candidate got what percent of vote for each county.  This would help candidates decide where to spend their time campaigning. For example: Diana DeGette, a Democrat, won 73.8% of the total vote, but did she win any of the 24,801 votes out of Arapahoe County? This type of data analyzation could show the voter demographic for the State of Colorado, it would also show candidates where they are most and least supported.









