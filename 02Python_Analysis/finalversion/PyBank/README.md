# Unit 2 | Homework Assignment: Automate Your Day Job with Python

1. Create a new GitHub repo called `python-analysis`. Then, clone it to your computer.

2. In your local git repository, create a directory for both of the Python activities. Use folder names that correspond to the activities: **PyBank** and **PyRamen**.

3. In each folder you just created, add a new file called `main.ipynb`. Remember that to create this file you will need to use JupyterLab to correctly generate the .ipynb file format. This will be the main notebook to run for each analysis.

4. Push the above changes to GitHub.

## PyBank

In this activity, you are tasked with creating a Python script for analyzing the financial records of your company. You will be provided with a financial dataset in this file: [budget_data.csv](PyBank/Resources/budget_data.csv). This dataset is composed of two columns,**Date and Profit/Losses**.

Your task is to create a Python script that analyzes the records to calculate each of the following:

**The total number of months included in the dataset.**

**The net total amount of Profit/Losses over the entire period.**

**The average of the changes in Profit/Losses over the entire period.**

**The greatest increase in profits (date and amount) over the entire period.**

**The greatest decrease in losses (date and amount) over the entire period.**

Your resulting analysis should look similar to the following:

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

Your final script should print the analysis to the terminal and export a text file with the results.