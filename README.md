# Election Analysis with Python

## Overview of Election Audit
In this project, we were tasked with using Python to complete the election audit of a recent local congressional election:

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Calculate the total number of votes from each county.
7. Calculate the percentage of votes from each county.
8. Determine which county had the largest voter turnout.

## Election-Audit Results
The analysis of the election shows that:
- There were 369,711 votes cast in the election.
- The number of votes and percentage of total votes for each county were:
  - Jefferson: 10.5% (38,855)
  - Denver: 82.8% (306,055)
  - Arapahoe: 6.7% (24,801)
- The county with the largest number of votes was:
  - Denver, with 306,055 votes.
- The candidates were:
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
- The candidate results were:
  - Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
  - Diana DeGette received 73.8% of the vote and 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
- The winner of the election was:
  - Diana DeGette, who received 73.8% of the vote and 272,892 votes.

## Election-Audit Summary
I propose that with some modifications, this script could be used for any election. To use the script on another state's congressional election, the value of the file_to_load variable would need to be changed to the name of a new CSV file with the results of that state's election, provided that the CSV file follows the same format as the current election_results.csv. 

If this script were to be used on the presidential election, the county vote counts and percentages could be replaced with the vote counts and percentages for each district in a certain state. Alternatively, it could calculate the total votes for each state and return the state with the highest turnout. The script would need to be modified further to give each presidential candidate the corresponding number of electoral college votes once they have won a certain state, and then return their total number of electoral college votes.
