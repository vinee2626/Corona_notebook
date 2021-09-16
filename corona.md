# Corona data analytics 

Resources : 
            https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset

            https://stackoverflow.com/
            
            

I have extracted this data-set from kaggle to perform basic data exploration on the data in regards to confirmed cases of corona, the number of deaths across provinces/states in every country/region.

The libraries in this project include pandas, matplotlib, seaborn and os to compute and visualize the data to answer certain meaningful questions in order to gain insight of the data.

After creating a dataFrame and reading the file from my csv file, I started this with data wrangling and reducing the noise by checking for any null, NaN data in my dataFrame and also getting rid of any unwanted values. 

# I have designed these questions by going through the data-set to have an in-depth view of the data:

- Which country had the maximum number of cases ?
- Which province in the world has maximum number of cases?
- How many total deaths have been confirmed until now?
- Which country had the highest number of deaths?
- How much the confirmed cases of corona caused to fuel the increase in number of deaths?
- Which country had the best recovery rate? 

# To answer these questions effectively the process I went through was:

- Reading data from csv file and create a new DataFrame.
- Created new dataframes when required and made changes to columns.
- Used groupby function to perform aggregate methods on this data.
- Used certain modules of matplotlib and seaborn to visualize the data in the form of customized bar charts and line charts.
- Used seaborn to define correlation using heatmap.
- Labelled those graphs.
- Renamed the column name.
