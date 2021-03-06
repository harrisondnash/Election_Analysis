# Overview of Election Audit

The Colorado Board of Elections requested an audit of a recent election. Software was implemted to complete the following tasks:
1. Total votes cast
2. List of candidates
3. Number of votes per candidate 
4. Percentage of votes per candidate per state
5. Winner!
6. How many people went to the polls per county
7. What capita percentile went to the polls
8. The county with the largest voter turnout

## Election Audit Results

This is to address the requested bulleted list:

- How many votes were cast in this congressional election?

    369,711 total votes were cast

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

    Jefferson: 10.5% (38,855)

    Denver: 82.8% (306,055)

    Arapahoe: 6.7% (24,801)

- Which county had the largest number of votes?

    Denver Co.

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

    Charles Casper Stockham: 23.0% (85,213)

    Diana DeGette: 73.8% (272,892)

    Raymon Anthony Doane: 3.1% (11,606) 

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

    Winner: Diana DeGette

    Winning Vote Count: 272,892

    Winning Percentage: 73.8%

## How this could be used

Summary statement: The electoral commision could use the following scripts to analize election results, both high and low:

Line 115   

if (votes > largest_county_count) and (percentage > winning_percentage): make < than instead of greater than for biggest loser 
same with 

line 152

if (votes > winning_count) and (vote_percentage > winning_percentage):

## Screenshot of election results

Please see the below .png file for terminal screenshot of results:

![image info](./img/terminal.png)











