# DATA612_WK1_ASGMT
**Homework Assignment Number 1/Data612 Overiew and Item Discussion: ****
We start by opening Jupyter Notebook and loading the 2010 State Drug Utilization dataset from the https://raw.githubusercontent.com/frankData612/master/State_Drug_Utilization_Data_2010/State_Drug_Utilization_Data_2010.csv file (Item 1).

Next load the dataset into pandas and import necessary pandas functions to utilize the dataset (Item 2).

Next, we show the top 10 rows and the bottom 10 rows using the **df.head(10)** and **df.tail(10)** syntax (Item 3).

We follow this by printing the Column Names using the **print(df.columns)** syntax (Item 4).

Next, we print the data types of the 2010 State Drug Utilization dataset using the **df.dtypes** **and df.info()** syntax (Item 5).

This is followed by printing the shape of our 2010 State Drug Utilization datset using the **df.shape** syntax.

Next, we printout the Summary Statistics using a series of pandas syntax commands (above).

Finally, we use the **df.groupby([' ', ' ']).mean()** syntax to review specific column "mean" values grouped by year and quarter.
