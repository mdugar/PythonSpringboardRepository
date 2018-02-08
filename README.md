# Python Project for working with JSON file with World Bank Data - Data Wrangling

There were 3 parts to this project
1. Find the 10 countries with most projects
2. Find the top 10 major project themes (using column 'mjtheme_namecode')
3. In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in.


1. 
a. This was done by getting the World Bank data file into a Dataframe
b. Next looking at Head snapshot of the DF gives one an understanding of the data.
c. Getting column Names was next so as to pick the right columns.
d. I ran the value_counts() function on the groupby 'countryshortname'
e. Taking a slice of the first 10 gives the 10 countries with the most projects since this list was by descending order.
