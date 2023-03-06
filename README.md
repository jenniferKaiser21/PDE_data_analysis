# Data Analysis of PDE Datasets
Data Analysis of PDE (Pennsylvania Department of Education) Datasets (2013 - 2022)
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_19.png">

Jennifer Kaiser 2023
www.jenniferkaiser.tech
www.linkedin.com/in/jenniferkaiser-tech
www.github.com/jenniferkaiser21

Exploration of Pennsylvania Department of Education Data

# Data Source(s):
https://www.education.pa.gov/DataAndReporting/Pages/default.aspx

# Languages Used:
* Python

# Packages/Libraries Used:
* pandas
* matplotlib
* numpy

# IDE Used:
* Jupyter Notebook

# Summary of Data Exploration: 
This project uses data from the Pennsylvania Department of Education to answer some basic questions regarding educators in the commonwealth of PA.
After importing the data using read_excel() and initializing the dataframes [cells 2- 3], I examined the contents of the df_13_14 and df_21_22 dataframes using head() [cells 4-7]. I noticed that some of the column titles were different, so I did some analysis to find the intersection of columns [cell 8], and the overall counts of common columns in each dataframe [cell 9]. I found that the "Active/Leave/Other" column data in the df_13_14 was the same as the "Status" column in df_21_22 [cells 10-11]. To ensure the values would be the same in each column, I identified the unique() values in "Active/Leave/Other" column data in the df_13_14 [cell 12], obtained .value_counts() for each [cell 13], and did the same for the "Status" column data in the df_21_22 [cell 14], and the .value_counts() [cell 15]. 

This led me to the question, what's the difference in frequency between 13/14 data and 21/22 data and the years in education? To explore this further, I first identified the .value_counts() of records in the "YearsInEd" column of df_13_14, sorting by the index (number of years in education) [cell 16], and again for the df_21_22, noting that the column is titled "YearsInED" with a capital "D" [cell 17]. 

I decided to plot the results using matplotlib. I wanted to compare the bar graphs side by side to see the overall trend of Number of Years in Education vs Number of Educators between 2013-2014 data and 2021-2022 data [cell 18].

The overall trend is clear, after about 5-8 years in Education, the retention of teachers drops off significantly in more recent years (2021-2022) than it does in earlier years (2013-2014). This shows the correlation between attrition and the National Teacher shortage that every state, including the Commonwealth of Pennsylvania is experiencing as of late.

I then plotted data from both dataframes together in a side-by-side bar graph to show the drastic difference between the two school years (2013-2014 vs 2021-2022) [cell 19].

# Future investigations:
I would love to dive deeper and find more trends in regards to attrition, particularly focusing on gender, average salary upon attrition, and attempting to determine other factors contributing to attrition. I would also use other datasets besides the 2013-2014 and 2021-2022 school years. Unfortunately, my computer was limited in capacity to load all the data sets at once, which is why certain years are commented out (but can easily be uncommented and rerun to include in analysis).

<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_2_3.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_4.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_5.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_6.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_7.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_8.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_9.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_10_11.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_12_15.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_16.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_17.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_18.png">
<img src="https://github.com/jenniferKaiser21/PDE_data_analysis/blob/e69ab19f2010380bb562a32b19bd47cda1bf7c20/images/cell_19.png">
