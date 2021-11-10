# **Election Analysis Challenge**
## **Overview of Election Audit**
The purpose of this analysis was to perform an audit of the results of a congressional election in the state of Colorado. The Colorado Board of Elections requested an analysis to be performed to be able to view the results of the election. The data was provided in a .CSV file and the following was required: 
* Total number of votes cast
* A complete list of candidates who received votes
* Total number of votes each candidate received
* Percentage of votes each candidate won
* The winner of the election based on popular vote

In addition to the above requirements we were tasked to expand the analysis to include:

* The voter turnout for each county
* The percentage of votes from each county out of the total count
* The county with the highest turnout

## **Election Audit Results**
Below are the results of our analysis:

![This is an image](https://github.com/AleksKostrycka/Election_Analysis/blob/main/Election%20Audit%20Results.png?raw=true)

* The total number of votes that were cast in this election: 369,711
* County Information:
  - Jefferson: Total number of votes in Jefferson County were 38,855 which is 10.5% of the total vote
  - Denver: Total number of votes in Denver County were 306,055 which is 82.8% of the total vote. 
  - Arapahoe: Total number of votes in Arapahoe County were 24,801 which is 6.7% of the total vote
* Denver County had the largest number of votes with 306,055 votes counted
* Candidate Information:
  - Charles Casper Stockham had 85,213 votes which is 23% of teh total vote
  - Diana DeGette had 272,892 number of votes which is 73.8% of the total vote
  - Raymon Anthony Doane had 11,606 votes which is 3.1% of the total vote
* Diana DeGette was the winner of this election with a total of 272,892 votes which is 73.8% of the total vote. 

## **Election Audit Summary**

The script that was written throughout the course of this analysis is adaquate and supports the ask of the audit committee, to extracts the results of this election. Currently the script extracts the candidate data as well as the county data and counts the votes per candiate and county. This is very useful information to quickly find out the results, and this can be easily adapted to any election that the data is provided for. However there are a few additional suggestions that would make the script more powerful to the user, a few modifications to the script will unlock even more knowledge locked in a data set. 

One modification that can be made to the script is to derive the per candidate vote with in each county, this way you can quickly tell who won the popular vote within each county. This can be useful in re-elections for those who might not have gotten a lot of votes in specific counties. Their focus can be narrowed during the next election. 

A second modification that can be made to the script to unlock more potential and use it for any election can be to expand the code and data to include more information about the voter. Identify specifcs about the population of voters(location, ethnicity, gender) and which political party they align with.  Including this type of inforamtion in the data, and amedning this script to read this information can be crucial for elections to hear the voice of the people. 

