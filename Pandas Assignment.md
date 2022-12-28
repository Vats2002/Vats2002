# PandasAssignment

Q1. How do you load a CSV file into a Pandas DataFrame?

ans1.Load the CSV into a DataFrame: import pandas as pd. df = pd.read_csv('data.     csv') ...
     Print the DataFrame without the to_string() method: import pandas as pd. ...
     Check the number of maximum returned rows: import pandas as pd. ...
     Increase the maximum number of rows to display the entire DataFrame: import pandas as pd.

Q2. How do you check the data type of a column in a Pandas DataFrame?

ans2.To check the data type in pandas DataFrame we can use the “dtype” attribute. The attribute returns a series with the data type of    each column. And the column names of the DataFrame are represented as the index of the resultant series object and the corresponding data types are returned as values of the series object.

Q3. How do you select rows from a Pandas DataFrame based on a condition?

ans3.Create a Pandas DataFrame with data. ...
     Selecting rows using loc[] ...
    Select rows based on condition using loc. ...
    Using 'loc' and '! ...
    Combine multiple conditions with & operator. ...
    Selected columns using loc. ...
    Using loc[] and isin() ...
    Selected column using loc[] and isin().

Q4. How do you rename columns in a Pandas DataFrame?

ans4.   # Import pandas package
import pandas as pd

# Define a dictionary containing ICC rankings
rankings = {'test': ['India', 'South Africa', 'England',
							'New Zealand', 'Australia'],
			'odi': ['England', 'India', 'New Zealand',
							'South Africa', 'Pakistan'],
			't20': ['Pakistan', 'India', 'Australia',
							'England', 'New Zealand']}

# Convert the dictionary into DataFrame
rankings_pd = pd.DataFrame(rankings)

# Before renaming the columns
print(rankings_pd)

rankings_pd.rename(columns = {'test':'TEST'}, inplace = True)

# After renaming the columns
print("\nAfter modifying first column:\n", rankings_pd.columns)


Q5. How do you drop columns in a Pandas DataFrame?

ans5. # Import pandas package
import pandas as pd

# create a dictionary with five fields each
data = {
	'A': ['A1', 'A2', 'A3', 'A4', 'A5'],
	'B': ['B1', 'B2', 'B3', 'B4', 'B5'],
	'C': ['C1', 'C2', 'C3', 'C4', 'C5'],
	'D': ['D1', 'D2', 'D3', 'D4', 'D5'],
	'E': ['E1', 'E2', 'E3', 'E4', 'E5']}

# Convert the dictionary into DataFrame
df = pd.DataFrame(data)

# Remove column name 'A'
df.drop(['A'], axis=1)


Q6. How do you find the unique values in a column of a Pandas DataFrame?

ans6.You can get unique values in column (multiple columns) from pandas DataFrame using unique() or Series. unique() functions. unique()  from Series is used to get unique values from a single column and the other one is used to get from multiple columns.

Q7. How do you find the number of missing values in each column of a Pandas DataFrame ?

ans7.   df. isnull(). sum() will give the column-wise sum of missing values.

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?

ans8. The fillna() method replaces the NULL values with a specified value. The fillna() method returns a new DataFrame object unless the inplace parameter is set to True , in that case the fillna() method does the replacing in the original DataFrame instead.

Q9. How do you concatenate two Pandas DataFrames?

ans9.    The concat() function in pandas is used to append either columns or rows from one DataFrame to another. The concat() function does all the heavy lifting of performing concatenation operations along an axis while performing optional set logic (union or intersection) of the indexes (if any) on the other axes.

Q10. How do you merge two Pandas DataFrames on a specific column?

ans10.You can join pandas Dataframes in much the same way as you join tables in SQL

      The concat() function can be used to concatenate two Dataframes by adding the rows of one to the other.

      concat() can also combine Dataframes by columns but the merge() function is the preferred way

      The merge() function is equivalent to the SQL JOIN clause. ‘left’, ‘right’ and ‘inner’ joins are all possible.

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?

ans11. In Pandas, we can also apply different aggregation functions across different columns. For that, we need to pass a dictionary with key containing the column names and values containing the list of aggregation functions for any specific column.
         
         # importing pandas package
import pandas as pd

# making data frame from csv file
df = pd.read_csv("nba.csv")

# We are going to find aggregation for these columns
df.aggregate({"Number":['sum', 'min'],
			"Age":['max', 'min'],
			"Weight":['min', 'sum'],
			"Salary":['sum']})


Q12. How do you pivot a Pandas DataFrame?

ans12.DataFrame.pivot(self, index=None, columns=None, values=None)
 
Q13. How do you change the data type of a column in a Pandas DataFrame?

ans13. import pandas as pd
      technologies = {
           'Courses':["Spark","PySpark","Hadoop","Python","pandas","Oracle","Java"],
           'Fee' :[20000,25000,26000,22000,24000,21000,22000],
           'Duration ':['30day','40days','35days', '40days','60days','50days','55days'],
           'Discount':[11.8,23.7,13.4,15.7,12.5,25.4,18.4]
        }
       df = pd.DataFrame(technologies)
       print(df.dtypes)

Q14. How do you sort a Pandas DataFrame by a specific column?

ans14.To sort the DataFrame based on the values in a single column, you'll use . sort_values() . By default, this will return a new DataFrame sorted in ascending order. It does not modify the original DataFrame.

Q15. How do you create a copy of a Pandas DataFrame?

ans15.The copy() method returns a copy of the DataFrame. By default, the copy is a "deep copy" meaning that any changes made in the  original DataFrame will NOT be reflected in the copy.

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?

ans16.Using Loc to Filter With Multiple Conditions
The loc function in pandas can be used to access groups of rows or columns by label. Add each condition you want to be included in the filtered result and concatenate them with the & operator. You'll see our code sample will return a pd. dataframe of our filtered rows.

Q17. How do you calculate the mean of a column in a Pandas DataFrame?

ans17.To calculate the mean of whole columns in the DataFrame, use pandas. Series. mean() with a list of DataFrame columns. You can also get the mean for all numeric columns using DataFrame.

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?

ans18.Standard deviation is calculated using the function . std() . However, the Pandas library creates the Dataframe object and then the function . std() is applied on that Dataframe .

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?

ans19.By using corr() function we can get the correlation between two columns in the dataframe.

Q20. How do you select specific columns in a DataFrame using their labels?

ans20.Selecting columns based on their name This is the most basic way to select a single column from a dataframe,
 just put the string name of the column in brackets. Returns a pandas series. Passing a list in the brackets lets you select multiple columns at the same time.

Q21. How do you select specific rows in a DataFrame using their indexes?

ans21.If you'd like to select rows based on integer indexing, you can use the . iloc function. If you'd like to select rows based on label indexing, you can use the . loc function.

Q22. How do you sort a DataFrame by a specific column?

ans22.    pandas.DataFrame.sort_values()

Q23. How do you create a new column in a DataFrame based on the values of another column?

ans23. You can add/append a new column to the DataFrame based on the values of another column using df. assign() , df. apply() , and, np. where() functions and return a new Dataframe after adding a new column.

Q24. How do you remove duplicates from a DataFrame?

ans24.Pandas DataFrame drop_duplicates() Method
The drop_duplicates() method removes duplicate rows. Use the subset parameter if only some specified columns should be considered when looking for duplicates.

Q25. What is the difference between .loc and .iloc in Pandas?

ans25.oc is label-based, which means that you have to specify rows and columns based on their row and column labels. iloc is integer position-based, so you have to specify rows and columns by their integer position values (0-based integer position).