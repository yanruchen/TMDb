# Investigate TMDb movie data 

<p>
  In this notebook, I investigate the movie data from [The Movie Database (TMDb)](https://www.themoviedb.org/)
</p>
<br/>

<p>
  I have explored two questions:
  <ul>
    <li> Does budget relate to vote average of the movie? </li>
    <li> What percent of the movie made no revenue? </li>
  </ul>

</p>

<br/>
<p>
  The notebook including data wrangling and exploratory data analysis.
</p>


<br/>

<p> 
In data wrangling, I first checked the general information, like the structure of data, missing values, duplicates. Then I cleaned the data by:
  <ul>
    <li> Find the duplicated row, and drop these data. </li>
    <li> Drop columns that are not relevant and have a lot missing value.</li>
    <li> Fill row with missing value. </li>
  </ul>

  
</p>

<br/>

<p>
In the exploratory data analysis, I did the following:

To answer first question "Does budget relate to vote average of the movie?",
  <ul>
    <li> Use scatter plot to explore the relationship between budget and avareage vote. </li>
    <li> Divide the vote into three bins, and use bar chart to visualize the budget in each category. </li>
  </ul>


To answer second question "What percent of the movie made no revenue?",
  <ul>
    <li> Separate the dataset by positive revenue or no revenue. </li>
    <li> Visualize the percentage of negative vs positive using pie chart.</li>
  </ul>

</p>



