<H1>NBA Data Analysis and Dashboard</H1>

<p>The National Basketball Association (NBA) is one of the most popular watched sports leagues in the world, with millions of fans tuning in to watch their favorite teams and players compete on the court. </p>

<p>In this project I used three diferents datasets</p>

The first can me found in this link: https://www.kaggle.com/datasets/ulrikthygepedersen/nba-player-salaries
This dataset provides a detailed breakdown of the salaries earned by NBA players based on their individual attributes and career trajectory.
The dataset includes information on a variety of player attributes, including age, height, weight, position, and years of experience. It also includes data on each player's career statistics, such as points per game, rebounds per game, and assists per game, among others.
By analyzing this data, fans and analysts can gain insights into how different attributes and career milestones impact NBA player salaries. They can also identify trends and patterns that might inform player evaluations and team-building strategies.
The dataset is updated daily with the latest results. I provide it in two formats for maximum accessibility:


The second and third datasets can be found in this link: https://www.kaggle.com/datasets/eoinamoore/historical-nba-data-and-player-box-scores
I used the PlayerStatistics.csv - The centerpiece of the dataset, this file contains detailed box scores for every individual player in NBA history, game by game.
And the Players.csv - Biographical information for every player, including height, weight, and position, enabling detailed player analysis across eras.
TeamHistories.csv

<ol> Steps:

  <li> Load the csv file:
    <ul>
      <li>Used the read_csv() to load my dataset into a Pandas DataFrame.</li>
    </ul>
  </li>

  <li>Explore the data>
    <ul>
      <li></li>Used the function head to call the first 5 rows of the dataset. </li>
      <li>Used the info function, that gives the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values).</li>
      <li>Used the describe function, that gives some statistical data like percentile, mean and standard deviation of the numerical values of the Series or DataFrame.</li>
    </ul>

  </li>

  <li>Identify and Handle Missing Values
3.1 - isnull
3.2 - dropna

  <li>Data Type Conversion
-In this dataset I Data from various sources are usually messy and the data types of some values may be in the wrong format, for example some numerical values may come in 'float' or 'string' format instead of 'integer' format and a mix up of these formats leads to errors and wrong results.

  <li>Padronizar e formatar dados

  <li>Filtrar e transformar dados

  <li>Save the data
-I saved the data using the df.to_csv(new_name.csv, index=False)
</ol>
