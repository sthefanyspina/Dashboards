<H1>TV Shows and Movies Data Analysis and Dashboard</H1>

<p>IMDB is one of the main sources which people use to judge the movie or show. IMDB rating plays an important role for a lot of people watching a movie or show. I watched Planet Earth II after finding out that it's at the top of the list on IMDB. I've created this dataset so that people can play with this dataset and do a lot of things as mentioned below. </p></br>

<p>In this project I used two diferents datasets</p>
<p>The first can me found in this link: https://www.kaggle.com/datasets/ulrikthygepedersen/nba-player-salaries](https://www.kaggle.com/datasets/karkavelrajaj/imdb-top-250-shows</p>
<p>This dataset is having the data of the top 250 Shows as per their IMDB rating listed on the official website of IMDB</p>

<p>The second dataset can be found in this link: [https://www.kaggle.com/datasets/eoinamoore/historical-nba-data-and-player-box-scores](https://www.kaggle.com/datasets/karkavelrajaj/imdb-top-250-movies)</p>
<p>This dataset is having the data of the top 250 Movies as per their IMDB rating listed on the official website of IMDB</p></br>

<p>Steps:</p>
<ol> 
  <li> Load the csv file:
    <ul>
      <li>Used the read_csv() to load my dataset into a Pandas DataFrame.</li>
    </ul>
  </li>

  <li>Explore the data:
    <ul>
      <li>Used the function head to call the first 5 rows of the dataset. </li>
      <li>Used the info function, that gives the number of columns, column labels, column data types, memory usage, range index, and the number of cells in each column (non-null values).</li>
      <li>Used the describe function, that gives some statistical data like percentile, mean and standard deviation of the numerical values of the Series or DataFrame.</li>
    </ul>
  </li>

  <li>Identify and Handle Missing Values:
    <ul>Used isnull function to identify missing values in the dataset.</ul>
    <ul>Used the replace function to replace all the empty rows with NAN.</ul>
    <ul>Used the dropna function to drop the missing/null values from our dataset.</ul>
  </li>

  <li>Data Type Conversion:
    <ul>In this dataset I didn't need to made any conversion, all the columns were with the correct types.</ul>
  </li>

  <li>Save the data
    <ul>I saved the data using the df.to_csv(new_name.csv, index=False)</ul>
  </li>
</ol>

![image](https://github.com/user-attachments/assets/d0320e84-5143-470e-bcfa-dfc0cfcd9f8c)
