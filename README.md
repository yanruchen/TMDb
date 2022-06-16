# Investigate TMDb movie data 

In this notebook, I investigate the movie data from [The Movie Database (TMDb)](https://www.themoviedb.org/)\

I have explored two questions:

1. Does budget relate to vote average of the movie?
2. What percent of the movie made no revenue?

The notebook including data wrangling and exploratory data analysis.

In data wrangling, I first checked the general information, like the structure of data, missing values, duplicates. Then I cleaned the data by:
1. Find the duplicated row, and drop these data.
2. Drop columns that are not relevant and have a lot missing value.
3. Fill row with missing value

In the exploratory data analysis, I did the following:

To answer first question "Does budget relate to vote average of the movie?",

1. Use scatter plot to explore the relationship between budget and avareage vote.
2. Divide the vote into three bins, and use bar chart to visualize the budget in each category.

To answer second question "What percent of the movie made no revenue?",

1. Separate the dataset by negative or positive revenue.
2. Visualize the percentage of negative vs positive using pie chart.




