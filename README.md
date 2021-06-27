# Election_Analysis

## Overview of Election Audit:
A Colorado Board of Elections employee has requested the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number votes cast.
2. Get a complete list of participating counties.
3. Calculate total votes each county casted.
4. Calculated the percentage of overall votes casted for each county. 
5. Determine which county had the most votes casted.
6. Get a complete list of candidates who received votes.
7. Calculate the total number of votes each candidate received.
8. Calculate the percentage of votes each candidate won.
9. Determine winning candidate based on popular vote and associated winning count and winning percentage.

## Resources
- [Voting Data Source: Election Results.csv](https://github.com/sbretag/Election_Analysis/blob/main/Resources/election_results.csv)
- Software: Python 3.8.8, Visual Studio 1.57.1
- [Python Script](https://github.com/sbretag/Election_Analysis/blob/main/PyPoll_Challenge.py)

## Audit Results

### Audit Results Output
![](https://github.com/sbretag/Election_Analysis/blob/main/Analysis/Election_Results_TextOutput.png)

[Terminal Output of Audit Results](https://github.com/sbretag/Election_Analysis/blob/main/Analysis/Election_Results_TerminalOutput.png)

## Election Audit Summary
Overall, the results of the audit were collected in an accurate and efficient manner using python code.  Given the success, we would like to propose handling all future election audits in both states and nationally.  The script used to perform an audit in this election is flexible and with minor modifications it can handle other types of elections with the same success.  Here are a few examples:
  1. Assuming the source data is available, we could provide more granuluar audit results by zip code by adding a new list for zip codes and creating votes by zip code dictionary.  By running through a similiar script as we did for county results, we could provide an output of vote count by zip code and zip code votes as % of overall total.
  2. For election results that have more than one type of race such as the house and senate, we could expand the script to include a list of the different races and a dictionary with a the candidates associated with each race.  In addition to adding data structures, a new for loop would need to be added to go through all of the different races and a condition would need to be added to filter on the candidates only associated with the particular race that's being analyzed in the for loop. 
  
