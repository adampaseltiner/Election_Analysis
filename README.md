# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given me the following tasks to complete the election audit of a recent local congressional election:

1. Calculate the total number of votes cast.
2. Get a complete list of counties where people voted.
3. Calculate the total number and percentage of votes in each county.
4. Determine the county with the largest voter turnout.
5. Get a complete list of candidates who received votes.
6. Calculate the total number and percentage of votes each candidate received.
7. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.6.7, Visual Studio Code, 1.56.0

## Election-Audit Results
The analysis of the election:
- There were 369,711 votes cast in the election.
- Votes were placed in three counties:
  - Jefferson: 38,855 votes, 10.5% of the total vote
  - Denver: 306,055 votes, 82.8% of the total vote
  - Arapahoe: 24,801 votes, 6.7% of the total vote
- The county with the largest voter turnout was Denver county.
- The candidates and their voting results:
  - Charles Casper Stockham: 85,213 votes, 23.0% of the total vote
  - Diana DeGette: 272,892 votes, 73.8% of the total vote 
  - Raymon Anthony Doane: 11,606 votes, 3.1% of the total vote
- The winner of the election:
  - Diana DeGette won the election with 272,892 votes, 73.8% of the total vote.

![Election Results](https://user-images.githubusercontent.com/82347825/117558731-be809400-b04d-11eb-8e58-ddc1784f5eba.png)


## Election-Audit Summary
After completing this analysis I have several propositions for the election commission regarding the use of this code for future elections:
  1. This script can readily be changed to accomodate any type of election (e.g. city, district, county, state, national) simply by updating the variables. The code structure of any election analysis will very closely mirror the analysis we did here and a simple update of the variable sets would accurately reflect the required inputs/outputs of a different election.
  2. Even if the quantity/fields of data increases, this script can be quickly scaled to analyze an infinitely large number of fields. In this project, expanding from candidate analysis to county analysis utilized almost the exact same type of code we had already written and thus we could apply that same code to look at further areas of interest (e.g. age, gender, race, income, etc.).
