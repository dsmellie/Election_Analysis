# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
-Data Source:election_results.csv
-Software: Python 3.9.2 Visual Studio Code 1.70.1

## Summary
The analysis of the election shows that:
- There were 369,711 votes cast in the election
- The candidates were:
    - Casper Stockham
    - Diana DeGette
    - Raymon Anthony Doane
- The candidate results were:
    - Casper Stockham received 23.0% of the vote and 85,213 votes
    - Diana DeGette received 73.8% of the vote and 272,892 votes
    - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes
- The winner of the election was:
    - Diana DeGette, who received 73.8% of the vote and 272,892 votes


## Challenge Overview

### Overview of Election Audit
The purpose of this analysis is to determine the winner of Colorado's congressional election and ensure the votes are appropriately counted and attributed to the correct candidate.

### Results 

#### How many votes were cast in this congressional election?
There were a total of 369,711 votes cast in this congressional election. 

#### Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
We received votes from three counties in this election: Arapahoe County, Jefferson County, and Denver County. The most votes were cast in Denver County, as 82.8% of all votes cast in this election were cast there (a total of 306,055 votes). 10.5% of the votes cast in this election were cast in Jefferson County (38,855 votes) and 6.7% of the votes cast in this election were cast in Arapahoe County (24,801 votes).

#### Which county had the largest number of votes?
As can be seen in the breakdown provided above, Denver County had the largest number of votes.

#### Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

Three candidates received votes in this election: Charles Casper Stockham, Diana Degette, and Raymon Anthony Doane. Diana Degette received the 73.8% of the votes cast in the election (272,892 votes) making her the winner of the election. Charles Casper Stockham received 23.0% of the votes (85,213 votes) and Raymon Anthony Doane received 3.1% of the votes (11,606 votes). 
#### Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
As can be seen in the breakdown provided above, Diana Degette received the 73.8% of the votes cast in the election (272,892 votes) making her the winner of the election.


## Challenge Summary
In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.


I propose that the Colorado election commission use this code, with some modifications, for all future elections. I have two suggestions for modifications that will enable it to function in other elections. First, instead of tracking votes by county, we can track votes by precint. As precint-level data is more granular, this feature will be useful for local elections where all the votes come from a single county. This change will require that the information provided indicates the precint the data comes from. Alternatively, when a election is at the county-level we can simply remove the data on which county each vote came from as all votes will be from one county. 

A second useful modification to the code would be to annouce that there is a tie in the case that two or more candidates receive the same number of votes. While such a result should rarely happen, it is important to not announce that one candidate won if the initial vote count indicates a tie. 
