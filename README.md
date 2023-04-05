# NBA Data Analysis
This data analysis project using NBA players data to predict salaries. In this project, Python's pandas, seaborn, matplotlib, numpy, and sklearn libraries are utilized for data wrangling, handling, and visualization.

## Summary:
<b>This project consists of five main sections, each with its specific objectives:</b>

* <b>Section 1 - Data Wrangling</b>
In the first section, we load the NBA players data into a pandas dataframe and drop the rows that contain missing values. Then, we reset the index and extract the 'Age', 'Height', 'Weight', and 'Salary' columns to examine their contents.

* <b>Section 2 - Handling 'Height' Column</b>
In the second section, we define a function called 'feet_to_inch' to convert the 'Height' column from feet to inches for more convenient handling. Then, we use the 'apply' and 'lambda' functions to perform the conversion and change the data type of the 'Height' column from string to float.

* <b>Section 3 - Positions Visualization</b>
In the third section, we create a countplot and pieplot for the 'Position' column to visualize the amount and order of each position.

* <b>Section 4 - Predicting Salaries</b>
In the fourth section, we define a model to predict NBA player salaries based on their age, height, and weight using the Decision Tree Classifier and Random Forest Classifier from the sklearn library. We also split the data into training and testing datasets.

* <b>Section 5 - Checking Our Model</b>
In the final section, we choose the best model to predict NBA player salaries based on the minimal Mean Squared Error (MSE) value. We evaluate the model's performance by comparing it to the standard deviation (STD) value of the salary data and examining the predicted salary values against the actual salary values in the testing dataset.
