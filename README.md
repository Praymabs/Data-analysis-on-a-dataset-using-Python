# Data-analysis-on-a-dataset-using-Python

The provided code performs data analysis on a dataset using Python and various libraries. Here's a summary of the code:<br><br>
A dataset is loaded from a Google Drive link into a Pandas DataFrame named df.<br>
The shape of the DataFrame is displayed, showing the number of rows and columns.<br>
Pandas options are set to display all columns and rows when printing DataFrames.<br>
Information about the DataFrame, such as column names, data types, and non-null values, is shown.<br>
The number of missing values for each column is calculated and displayed.<br>
The percentage of missing values for each column is calculated and displayed.<br>
Columns with missing values exceeding 20% are identified and stored in missing_value_clm_gre_20.<br>
The DataFrame is updated by dropping the identified columns with excessive missing values.<br>
Numeric columns (int64 and float64) are selected from the updated DataFrame into df3_num.<br>
Rows containing missing values in the numeric columns are identified.<br>
The number of missing values for each numeric column is calculated and displayed.<br>
Numeric columns with missing values are stored in missing_num_var.<br>
Density plots are created for each numeric column with missing values, showing the original distribution.<br>
Missing values in the numeric columns are filled with the column mean in df4_num_mean.<br>
The total number of missing values in df4_num_mean is calculated and displayed.<br>
Density plots are created for each numeric column with missing values, comparing the original and mean-filled distributions.<br>
Missing values in the numeric columns are filled with the column median in df5_num_median.<br>
The total number of missing values in df5_num_median is calculated and displayed.<br>
Density plots are created for each numeric column with missing values, comparing the original, mean-filled, and median-filled distributions.<br>
Box plots are created to visualize the distribution and outliers of each numeric column in the original, mean-filled, and median-filled DataFrames.<br><br>
Overall, the code focuses on handling missing values in numeric columns using mean and median imputation, and visualizing the impact of imputation on the distribution and outliers of the data.
