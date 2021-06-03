# python-homework
## Python project, week 2


This python project reads and manipulates the data from a csv file and outputs the results into a separate output.txt file.

The original csv file contans dates and corresponsing profits/losses. The new txt file outputs the following:

* The total number of months included in the dataset.
* The net total amount of Profit/Losses over the entire period.
* The average of the changes in Profit/Losses over the entire period.
* The greatest increase in profits (date and amount) over the entire period.
* The greatest decrease in losses (date and amount) over the entire period.


In order to complete the task, I went through the following steps:

1. Read the original csv file and output the result.
2. Looped through the csv file data to calculate the sum of total profits/losses and the total number of periods.
3. Converted csv file into a dictionary to further create a separate lists of dates and profits/losses.
4. Converted a profits/losses list into integers.
5. Iterated through the profits/losses list to create a new list of daily changes and to calculate the average daily change.
6. Combined the lists of dates and changes into a new dictionary.
7. Looped through the dictionary to output the greatest increase and decrease changes with the matching dates.
8. Created the output.txt file with the results.


Below are the links to the code and supplementing materials:

*[The code](PyBank/main.ipynb)

