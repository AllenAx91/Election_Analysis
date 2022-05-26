# Election_Analysis 🗳️

## 1. Overview of Project
The election commission of the USA has requested an audit of the recent county elections. Seth and Tom, who are in charge of this project, have come to our aid in writing a Python program that would generate a concise report which includes the following deliverables. 

### 1.1. Deliverables 
  1) Total number of votes cast
  2) A complete list of candidates who received votes
  3) Total number of votes each candidate received
  4) Percentage of votes each candidate won
  5) The winner of the election based on popular vote
  6) The voter turnout for each county
  7) The percentage of votes from each county out of the total count
  8) The county with the highest turnout

## 2. Election Audit Results

The python code ran successfully, satisfying all deliverable requirements. 

_Image of analysis_

![](https://github.com/AllenAx91/Election_Analysis/blob/main/analysis/Print_Txtfile.png))

### 2.1. Highlights
Candidate _Diana DeGette_ won the prescient elections with a huge support from _73.8% of voters_ from a total of **369,711 votes**. **Denver** had the majority of the voters reporting for election day.
### 2.2. Breakdown: Total votes vs Individual county
Arapahoe and Jefferson were well behind Denver, registering only 6.71% and 10.51% of the total votes. This gap could be attributed to various factors, some of which could be due to the low population in these counties, lack of awareness of the election and low confidence in the candidates. Further analysis would be required to assess the cause of the poor turnout in Arapahoe and Jefferson. 

_Key:_ County Name: Percentage of County votes out of total votes (Number of votes from County)

_Details:_
 * Jefferson: 10.51% (38,855) 🥈
 * Denver: 82.78% (306,055) 🥇
 * Arapahoe: 6.71% (24,801) 🥉
 ### 2.3. Breakdown: Candidate results vs Total votes
 From the below list, one can infer that the high confidence placed in Diana has resulted in her victory with a large margin. 

_Key:_ Candidate Name: Percentage of candidate votes out of total votes (Number of votes for Canidate)

_Details:_
 * Charles Casper Stockham: 23.0% (85,213) 🥈
 * Diana DeGette: 73.8% (272,892) 🥇
 * Raymon Anthony Doane: 3.1% (11,606) 🥉

## 3. Election-Audit Summary
Python is a flexible option to replicate the analysis done on other datasets. The below two options could be considered the most viable for the Election commission. 
 * Analysis can be done for other precincts by simply populating the source file [election_analysis.txt](https://github.com/AllenAx91/Election_Analysis) with the relevant county's data 
 * Furthermore, this code has the potential to analyze results for other elections as well. Instead of counties, data from state and national elections can be assessed
