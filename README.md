# Overview of Election Audit
***
The purpose of this election audit analysis was to provide additional information to the election commission for their audit. Specifically the commission requested the following: 
    
* The voter turnout for each county

* The percentage of votes from each county out of the total count

* The county with the highest turnout 
As  result the python code was update to reflect this data as evidenced below. 

## Election Audit Results
***

* In total there were 369,711 total votes cast in the election.
* There were three counties in the election, below is a breakdown of their total votes and vote percentages: 
    
    - Jefferson: 10.5% (38,855)
    - Denver: 82.8% (306,055)
    - Arapahoe: 6.7% (24,801)

* Denver had the largest number of votes cast overall totaling 306,055 votes. 

* There were three candidates in the election, below is a breakdown of their total votes and vote percentage:
    - Charles Casper Stockham: 23.0% (85,213)
    - Diana DeGette: 73.8% (272,892)
    - Raymon Anthony Doane: 3.1% (11,606)

* Winning canidate information as follows: 
    - Winner: Diana DeGette
    - Winning Vote Count: 272,892
    - Winning Percentage: 73.8%

* Screenshot of text file output from code below for reference: 
    - f
## Election-Audit Summary 
***
* This code successfully output the results for these counties in Colorado, but are applicable anywhere in the state mainly due to the following:
    - None of the candidate info is hard coded into the python file, therefore as long as data contains a ballot id, candidate, and county any additional or different candidate data can be used. 
    - Similarly none of the county info is hard coded, so as long as the data contains a ballot id, candidate, and county and additional or different counties can be used. 
    - These two features are due to the fact that the code makes a list of counties and candidates based on the data itself and not on an input in the code itself, thus its dynamic to what the input of the code is. 
    -Example of the code as follows which shows the creation of the respective county and candidate lists which gets populated as the code loops through the data. The entire code is available in the GitHub repo if a more in depth look is needed. 

  