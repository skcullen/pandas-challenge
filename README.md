# pandas-challenge
Unit 4: PANDAS HOMEWORK 

Included in this repository is my solution for the Unit 4: Pandas Homework for the Georgia Tech Analytics Bootcamp.

We were asked to write a script using Jupyter Notebook that would take the raw data from purchase_data.csv which details the in game purchases for a new game Heroes of Pymoli, and provide summary analysis based on different demographics and groupings. The tables that are included in this script: Player Count, Purchasing Analysis (Total), Gender Demographics, Purchasing Analysis (Gender), Age Demographics, Purchasing Analysis (Age), Top Spenders, Most Popular Items, and Most Profitable Items.

The notebook provided goes through the creation of each of the tables, as well as some of the steps I took in order to check on the data. I merged all the individual cells for each table, so that it was easier to tell what calculations went into a table. This is not the best format to check one's work, but Jupyter makes it so cells are easily split again. One had to be careful when calculating the values for the demographics, because there were certain players who made purchases more than one. I had to create a separte dataframe that only counted each player once. 

The only real stumbling block that I hit was getting the data from the dataframes that had been grouped. Since those values are only in a desirable format after they have gone through some sort of calculation. This forced me to reverse engineer the Item Price for the final two tables rather than just grabbing it from the dataframe.

At the very end of the Jupyter Notebook there is a cell detailing some of my observations from the analysis done, as well as some queries into what other analysis into Heroes of Pymoli could bring out.

Includes:
1. The Jupyter Notebook that is the main script for this assignment, HeroesMain.ipynb.
2. A Resources folder that holds the original dataset for Heroes of Pymoli
