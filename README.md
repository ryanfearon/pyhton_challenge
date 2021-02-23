# python_challenge
pythonHW3

Python Homework - Py Me Up, Charlie


Background
Well... you've made it!
It's time to put away the Excel sheet and join the big leagues. Welcome to the world of programming with Python. In this homework assignment, you'll be using the concepts you've learned to complete the two Python Challenges, PyBank and PyPoll.
Both of these challenges encompass a real-world situation where your newfound Python scripting skills can come in handy. These challenges are far from easy so expect some hard work ahead!

Before You Begin


Create a new repository for this project called python-challenge. Do not add this homework to an existing repository.


Clone the new repository to your computer.


Inside your local git repository, create a directory for each Python Challenge. Use folder names corresponding to the challenges: PyBank and  PyPoll.


Inside of each folder that you just created, add the following:

A new file called main.py. This will be the main script to run for each analysis.
A "Resources" folder that contains the CSV files you used. Make sure your script has the correct path to the CSV file.
An "analysis" folder that contains your text file that has the results from your analysis.



Push the above changes to GitHub or GitLab.



PyBank



In this challenge, you are tasked with creating a Python script for analyzing the financial records of your company. You will give a set of financial data called budget_data.csv. The dataset is composed of two columns: Date and Profit/Losses. (Thankfully, your company has rather lax standards for accounting so the records are simple.)


Your task is to create a Python script that analyzes the records to calculate each of the following:


The total number of months included in the dataset


The net total amount of "Profit/Losses" over the entire period


Calculate the changes in "Profit/Losses" over the entire period, then find the average of those changes


The greatest increase in profits (date and amount) over the entire period


The greatest decrease in losses (date and amount) over the entire period




As an example, your analysis should look similar to the one below:
Financial Analysis
----------------------------
Total Months: 86
Total: $38382578
Average  Change: $-2315.12
Greatest Increase in Profits: Feb-2012 ($1926159)
Greatest Decrease in Profits: Sep-2013 ($-2196167)


In addition, your final script should both print the analysis to the terminal and export a text file with the results.
