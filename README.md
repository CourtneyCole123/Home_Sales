<h1>Module 22 Challenge: Big Data</h1>

<h2>Background:</h2>
<p>In this challenge, you'll use your knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.</p>

<h2>Requirements:</h2>

- A Spark DataFrame is created from the dataset.

  [insert image here]

- A temporary table of the original DataFrame is created.

  [insert image here]

- A query is written that returns the average price, rounded to two decimal places, for a four-bedroom house that was sold in each year.

  [insert image here]

- A query is written that returns the average price, rounded to two decimal places, of a home that has three bedrooms and three bathrooms for each year the home was built.

  [insert image here]

- A query is written that returns the average price of a home with three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet for each year the home was built rounded to two decimal places.

  [insert image here]

- A query is written that returns the average price of a home per "view" rating having an average home price greater than or equal to $350,000, rounded to two decimal places. (The output shows the run time for this query.)

  [insert image here]

- A cache of the temporary "home_sales" table is created and validated.

  [insert image here]

- The query from step 6 is run on the cached temporary table, and the run time is computed.

  [insert image here]

- A partition of the home sales dataset by the "date_built" field is created, and the formatted parquet data is read.

  [insert image here]

- A temporary table of the parquet data is created.

  [insert image here]

- The query from step 6 is run on the parquet temporary table, and the run time is computed.

  [insert image here]

- The "home_sales" temporary table is uncached and verified.

  [insert image here]
