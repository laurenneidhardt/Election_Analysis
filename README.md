# Election Analysis #

## Project Overview ##

### 1.Overview of Election Audit: ###
  The purpose of this analysis was to quickly provide reliable election results and statistics to election officials. 
  
### 2. Election-Audit Results: ###  
* How many votes were cast in this congressional election?
![Total_Votes](https://github.com/laurenneidhardt/Election_Analysis/blob/main/Total_Votes.PNG)

* Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
![County_Votes](https://github.com/laurenneidhardt/Election_Analysis/blob/main/County_Votes.PNG)

* Which county had the largest number of votes? Denver

* Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.
![Candidates](https://github.com/laurenneidhardt/Election_Analysis/blob/main/Candidates.PNG)

* Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
![Winner](https://github.com/laurenneidhardt/Election_Analysis/blob/main/Winner.PNG)

### 3.Election-Audit Summary ###
This script could be utilized with almost any basic election data. Modifications could be made to the script in the lines that reference the columns in the raw election data .csv, to account for candidate name or county being in other locations in a table. If more specific data was wanted like totals by voting precinct, etc, that data could be added to the source .csv table and the code could be duplicated much as it has to accomdate totals for county. The script is general enough that any state, county or town could use it, by just adjusting the reference columns and changing the variable names to be more recognizable. The script is simply looking for the data and totaling up statistics usings for loops, so the data set could be even larger and still be accomodated. 

