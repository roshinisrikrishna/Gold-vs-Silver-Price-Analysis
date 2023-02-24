Gold vs Silver Price Growth Rate Comparison

Datasets:

We have a dataset downloaded from kaggle website. It is named as Gold_Price_Data. It contains gold prices from the year January 2008 to the year May 2018. This contains gold prices on daily basis. The data file is a Comma separated value file format with 2290 rows and 7 columns. It contains 5 columns which are numerical in datatype and one column in Date format. The dataset contains the values of the variables SPX,GLD,USO,SLV,EUR/USD against the dates in the date column. The following are: GLD - Gold price USO - United States Oil Price SLV - Silver Price EUR/USD - Currency pair i.e, value of 1 USD in EUR link - https://www.kaggle.com/datasets/altruistdelhite04/gold-price-data

PreProcessing:

We preprocess all the data by using basic techniques like dropping all the rows with missing values (there weren’t any!). The most preprocessing was done to the dates, since the data was collected from different sources, the dates were in different formats and they were formatted to a common format which would be understood by matplotlib for plotting it appropriately. The main preprocessing to be done for this analysis is to remove all the other unnecessary columns from the dataset. The necessary columns for this analysis are Date, GLD, SLV.

Exploratory Data Analysis:

At first, we create a pivot table with 3 columns with Date, GLD, SLV. Create a plot using plot() function to find the growth rate of the Gold and Silver prices against date.
