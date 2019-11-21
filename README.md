# Project tss_2019_2

Read the questions carefully and submit your answers

1.- Create a numeric vector that contains the eight planets of our solar system. Then, create another vector containing the name for each planet (Mercury, Venus, Earth, Mars, Jupiter, Saturn, Uranus, and Neptune). After that,  you should assign the number of the planet and its respective name. Finally, you should  select and print the planets related to the names Earth, Mars, and Jupiter.

2.- Construct a matrix with 10 rows containing the numbers 1 up to 50, filled row-wise.

3.-Create a factor with these observations "Breakfast", "Breakfast", "Breakfast", "Luch", "Luch", "Dinner", "Dinner", "Dinner", "Collation", "Collation", "Collation"  and print a summary.

4.- Create and print a data frame that should contain:
- 5 of your courses (e.g. Fundamentals of Programming, Object-Oriented Programming, Databases, etc ).
- 5 of your marks
- 5 of your professors' names


5.- Load the dataset labeled as **odb.csv** that is located in the **data** folder and storage this dataset in a variable called **od**.   Then, you should describe the composition of the dataset. This description must contain the number of  observations, variables and the type of each variable.


6.- Filter the **od** dataset to retrieve only the observation from Mexico, grouped by year and  in descending order selecting the  "ODB_Rank column

7.- Create a new variable called **od_year** grouping per "year"  and "Income group" variables. Then, remove  NAs observations. Later, using the function summarize() you should  estimate the median  of the GDP_PPP variable and store it in a variable called "medianValue"

8.-Create a line plot graph to visualize trends over time. You should use the variables created in the **od_year** data frame using `Income group` as color

9.- Create a new variable called **od_latin** filtering per Region, selecting Latin America & Caribbean and grouping per Income group. 

Then, using this data frame, create a plot visualizing the relationship between Individuals_using_Internet and GDP_PPP  colored per Income group and faceting per Economy


10.- Create a new variable called **od_2016** filtering the year 2016 and removing observations that contain NAs. 

Then, using this data frame, create a plot visualizing the relationship between Technological adoption and GDP_PPP,  colored per Income group. Furthermore,  you should use a log scale in both axes ("x" and "y"). Finally, you should use the facet function in order to wrap by Region.


Good luck and happy coding!!
