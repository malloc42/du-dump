# Semester-II (Data Analysis and Visualization using Python)
Practical Questions for UoD (NEP-UGCF) Year-I Generic Elective-II (Computer Science)<br>
**Semester-II (JAN2024) GE-II Data Analysis and Visualization using Python (Computer Science)**

[Reading for Semester-II](https://drive.google.com/file/d/1eOUavD7dz0vtvA-DwaEDJZ3x83rIWFpq/view?usp=sharing)

Note:

<ul>
  <li>Any platform for Python can be used for lab exercises</li>
  <li>Use a data set of your choice from Open Data Portal (https://data.gov.in/, UCI repository) or load from scikit, seaborn library for the following exercises to practice the concepts learnt.</li>
</ul>
<ol>
  <hr>
  <li>
    Write programs in Python using NumPy library to do the following:
  </li>
  <ol>
    <li>Compute the mean, standard deviation, and variance of a two dimensional random integer array along the second axis.</li>
    <li>Create a 2-dimensional array of size m x n integer elements, also print the shape, type and data type of the array and then reshape it into an n x m array, where n and m are user inputs given at the run time.</li>
    <li>Test whether the elements of a given 1D array are zero, non-zero and NaN. Record the indices of these elements in three separate arrays.</li>
    <li>Create three random arrays of the same size: Array1, Array2 and Array3. Subtract Array 2 from Array3 and store in Array4. Create another array Array5 having two times the  values in Array1. Find Co-variance and Correlation of Array1 with Array4 and Array5 respectively.</li>
    <li>Create two random arrays of the same size 10: Array1, and Array2. Find the sum of the first half of both the arrays and product of the second half of both the arrays.</li>
  </ol>
  <hr>
  <li>Do the following using PANDAS Series:</li>
  <ol>
    <li>Create a series with 5 elements. Display the series sorted on index and also sorted on values seperately</li>
    <li>Create a series with N elements with some duplicate values. Find the minimum and maximum ranks assigned to the values using 'first' and 'max' methods</li>
    <li>Display the index value of the minimum and maximum element of a Series</li>
  </ol>
  <hr>
  <li>Create a data frame having at least 3 columns and 50 rows to store numeric data generated using a random function. Replace 10% of the values by null values whose index positions are generated using random function. Do the following:</li>
  <ol>
    <li>Identify and count missing values in a data frame.</li>
    <li>Drop the column having more than 5 null values.</li>
    <li>Identify the row label having maximum of the sum of all values in a row and drop that row.</li>
    <li>Sort the data frame on the basis of the first column.</li>
    <li>Remove all duplicates from the first column.</li>
    <li>Find the correlation between first and second column and covariance between second and third column.</li>
    <li>Discretize the second column and create 5 bins.</li>
  </ol>
  <hr>
<li>
  Consider two excel files having attendance of two workshops. Each file has three fields 'Name', 'Date', 'Duration
(in minutes)' where names are unique within a file. Note that duration may take one of three values (30, 40, 50)
only. Import the data into two data frames and do the following:</li>
  <ol>
   <li>Perform merging of the two data frames to find the names of students who had attended both workshops.</li> 
    <li>Find names of all students who have attended a single workshop only.</li>
    <li>Merge two data frames row-wise and find the total number of records in the data frame.</li>
    <li>Merge two data frames row-wise and use two columns viz. names and dates as multi-row indexes. </li>
  </ol>
  <br>
Generate descriptive statistics for this hierarchical data frame.<hr>
  
  <li>
    Using Iris data, plot the following with proper legend and axis labels: (Download IRIS data from: https://archive.ics.uci.edu/ml/datasets/iris or import it from sklearn datasets)</li>
    <ol>
      <li>Plot bar chart to show the frequency of each class label in the data.</li>
      <li>Draw a scatter plot for Petal width vs sepal width and fit a regression line</li>
      <li>Plot density distribution for feature petal length.</li>
      <li>Use a pair plot to show pairwise bivariate distribution in the Iris Dataset.</li>
      <li>Draw heatmap for the four numeric attributes</li>
      <li>Compute mean, mode, median, standard deviation, confidence interval and standard error for each feature</li>
      <li>Compute correlation coefficients between each pair of features and plot heatmap</li>
    </ol>
    
  <hr>
  <li>
    Consider the following data frame containing a family name, gender of the family member and her/his monthly
income in each record.</li>

| Name  | Gender | MonthlyIncome (Rs.) |
| :---: | :----: | :-----------------: |
| Shah  |  Male  |      114000.00      |
| Vats  |  Male  |      65000.00       |
| Vats  | Female |      43150.00       |
| Kumar | Female |      69500.00       |
| Vats  | Female |      155000.00      |
| Kumar |  Male  |      103000.00      |
| Shah  |  Male  |      55000.00       |
| Shah  | Female |      112400.00      |
| Kumar | Female |      81030.00       |
| Vats  |  Male  |      71900.00       |

Write a program in Python using Pandas to perform the following:

<ol>
  <li>Calculate and display familywise gross monthly income.</li>
  <li>Calculate and display the member with the highest monthly income.</li>
  <li>Calculate and display monthly income of all members with income greater than Rs. 60000.00.</li>
  <li>Calculate and display the average monthly income of the female members</li>
</ol>
<hr>
<li>
  Using Titanic dataset, to do the following:</li>
  <ol>
    <li>Find total number of passengers with age less than 30</li>
    <li>Find total fare paid by passengers of first class</li>
    <li>Compare number of survivors of each passenger class</li>
    <li>Compute descriptive statistics for any numeric attribute genderwise</li>
  </ol>
  <hr>
</ol>

**Project**: students are encouraged to work on a good dataset in consultation with their faculty and apply the concepts learned in the course.
