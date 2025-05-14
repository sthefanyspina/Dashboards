<H1>Games Sales Dashboard</H1>

<p>The National Basketball Association (NBA) is one of the most popular watched sports leagues in the world, with millions of fans tuning in to watch their favorite teams and players compete on the court. </p></br>

<p>In this project I used the Video Games Sales dataset</p>
<p>The first can me found in this link: https://www.kaggle.com/datasets/anandshaw2001/video-game-sales</p>
<p>This dataset contains video game sales data across different platforms, genres, and regions, making it valuable for various analytical and business use cases. </p> </br>

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

![image](https://github.com/user-attachments/assets/3e05e08b-526f-429e-a9bd-4e51c39fdc6e)

