# Election_Analysis
## Project Overvieew
I will give an analysis of a local congressional election. By doing the following:

1. Calculating the total number of votes cast.
2. Getting the complete list of candidates who received votes.
3. Calculating the total number of votes each candidate recieved.
4. Calculating the percentage of votes each candidate won.
5. Determining the winner of the election based on number of votes.
6. Determining which county had the largest number of voters.

## Resources
-Data Source: election_results.csv

-Software: Python 3.7.6, Visual Studio Code, 1.49.2

## Summary
![](https://github.com/alainacox/Election_Analysis/blob/main/election_results.png)

In this project I have analyzed election data for a small rural town to help them determine the winner of their election. Using Python I was able to evaluate the total number of votes cast in the election, the total number of votes cast for each candidate, and the percentage of the votes that each candidate received.In order to print the results of the election by candidate, I created a code that ran through a For Loop and added to the “results” string variable. To make this work, I needed to open my csv file using the ‘r’ code instead of a ‘with open()’. By reading the csv file this way, I was able to interrupt my data reading without breaking the string of the ‘open with()’ command. I also used a ‘get’ function to access the Key candidate name and total votes in my dictionary of total votes. This allowed me to print the name and the results in the same command.
I modified the script so that it would give me the number votes per county. As well so that it would also show the percentage of votes per county. In doing that it will show any one who would want to run for the next election what county they would need to focus on and where you might want to get more people to vote. 

In this election, the candidate Diana DeGette was the winner with 73.8% of the votes. 
For the county Denver had the largest amount of voters at 82.8%.
