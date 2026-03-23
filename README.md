# F1-SQL-Project
Querying a small F1 historical dataset, with three tables, to gain insight into historical trends and all-time leaders.

## Overview + Repo Structure
My aim coming into this project, while ostensibly to practice SQL, was to look into historical F1 data and see how older drivers stacked up to current drivers. SQL proved to be a perfect tool for this - with three tables, one of my queries utilized a join function to cross-examine data. Another utilized a CTE to simplify a larger query, and yet another used a window function to rank the longest races of each driver.

From this I was able to find out about many interesting facts, including Mercedes having more than half of Ferrari's points with only one tenth of the driver count, or that George Russell has the fastest lap of anyone in the 21st century.

The folders "Query Results" and "Screenshots" show the list of images that I provide in the analysis below. "Raw_Data" contains the db and sqbpro files that I performed my analysis on.

Enjoy!

## Data Cleaning
![Cleaning step](Screenshots/Cleaning.png)

This was the only cleaning step I required; the data was already cleaned with the exception of every other line being blank for some reason.

## Query 1
![Q1](Screenshots/Query%201.png)
![Q1R](Query%20Results/Query%201%20Output.png)

## Query 2
![Q2](Screenshots/Query%202.png)
![Q2R](Query%20Results/Query%202%20Output.png)

## Query 3
![Q3](Screenshots/Query%301.png)
![Q3R](Query%20Results/Query%203%20Output.png)

## Query 4
![Q4](Screenshots/Query%204.png)
![Q4R](Query%20Results/Query%204%20Output.png)

## Query 5
![Q5](Screenshots/Query%205.png)
![Q5R](Query%20Results/Query%205%20Output.png)

## Query 6
![Q6](Screenshots/Query%206.png)
![Q6R1](Query%20Results/Query%206%20Output-PRO.png)
![Q6R2](Query%20Results/Query%206%20Output-HAM.png)
![Q6R3](Query%20Results/Query%206%20Output-MSC.png)

## Query 7
![Q7](Screenshots/Query%207.png)
![Q7R](Query%20Results/Query%207%20Output.png)
