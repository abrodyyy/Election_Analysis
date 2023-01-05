# Election_Analysis
## Project Overview
A Colorado Board of Elections employee has given the following tasks to complete an election audit of a recent local congressional election.
1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
Data Source: [election results.csv]([https://github.com/user/repo/blob/branch/other_file.md](https://github.com/abrodyyy/Election_Analysis/blob/main/Resources/election_results.csv))
- Software: Python 3.9.12, Visual Studio Code, 1.70.2

## Overview of Election Audit
We are assisting the Coloardo Board of Elections in obtaining additional information on a previous congressional election. To accomplish this, we've written a python script that will pull usefull information from the raw data. We've also made sure to include descriptions detailing each step of the script so that it can be used and refactored as needed for future elections. 

## Election Audit Results
The analysis of the election show that:

_There were 369,711 votes cast in the election._

**Candidates & results:**
Candidate                | Percentage of Votes | Count of Votes
------------------------ | ------------------- | --------------
Charles Casper Stockham  | 23.0%               | 85,213
:star:  Diana DeGette    | 73.8%               | 272,892
Raymon Anthony Doane     | 3.1%                | 11,606


<details>
           <summary>:star:  The winner of the election was:</summary>
           <p>Diana DeGette, who received 73.8% of the vote for a total of 272,892 votes.</p>
         </details>


**Counties & results:**

County                   | Percentage of Votes | Count of Votes
------------------------ | ------------------- | --------------
Jefferson                | 10.5%               | 38,855
:star:  Denver           | 82.8%               | 306,055
Arapahoe                 | 6.7%                | 24,801

<details>
           <summary>:star:  The county with the largest voter turnout was:</summary>
           <p>Denver, who received 82.8% of the vote for a total of 306,055 votes.</p>
         </details>


## Election Audit Summary
As previously mentioned, this python script can be used for any past or future election. We can make small chanegs to the script as needed, depending on the information provided in the raw data, and the details we're looking to obtain. For example - if we were looking at a United States presidential election, we would change county votes to state votes. Another example could be examinined the vote in the House of Representatives for Speaker of the House. We could change county to state and then also duplicate that code block and change state to political party. This would allow us to see the number of republican and democratic votes. If you're familiar with python, this script can be refactored and built upon in multiple ways as needed to include additional information if provided in the raw data. 
