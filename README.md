# PBL
A project created to read data from a csv file and that data is stored in particular format.
Basically a CSV file is given which contains the records of life expectancies of all countries of the world for each year.
This project reads that csv file and creates a HashTable to store the record of life expectancies of all countries for a year, means for every year it creates a HashTable.
Then queues (one for each year) are created from hashtable storing country names based on life expectancy in ascending order.  
Then  a stack is created containing the countries names based on the best life expectancy (average of all years 
given in the dataset) on top.
Then following four questions are solved using these three data Structures : HashTable, Queue and Stack.
Problem 1: How to find out which countries were providing best life expectancy during year 1962 and 
1964. 
Problem 2: How to search and display life expectancy of a country in each year using Step 1. 
Problem 3: Which country is providing best, average and worst life expectancy (Use step 3 data structure). 
Postulate 1: Is it true that the countries whose name start with A are providing better life expectancy than 
the rest of the countries. 
