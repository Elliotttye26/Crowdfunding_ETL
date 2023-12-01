# Crowdfunding_ETL

# The Challenge
For the ETL mini project, you will work with a partner to practice building an ETL pipeline using Python, Pandas, and either Python dictionary methods or regular expressions to extract and transform the data. After you transform the data, you'll create four CSV files and use the CSV file data to create an ERD and a table schema. Finally, you’ll upload the CSV file data into a Postgres database.
Since this is a one-week project, make sure that you have done at least half of your project before the third day of class to stay on track.
Although you and your partner will divide the work, it’s essential to collaborate and communicate while working on different parts of the project. Be sure to check in with your partner regularly and offer support.

# The Process
The process began by loading the dataset into a Pandas DataFrame from a CSV file and cleaning the data by addressing issues like missing values and duplicates. This ensured a high-quality dataset for analysis.
The next step involved exploring the data, where key variables were visualized to uncover patterns using Matplotlib. The focus then shifted to sentiment analysis, categorizing reviews as positive, negative, or neutral. Option one of using python dictionaries was implemented in this project to create the contact csv. Matplotlib was also used for visualizing findings through charts.
In the final stages, PostgreSQL was chosen to efficiently import CSV files, and code was employed to display data tables for a closer look. This comprehensive approach, covering data cleaning, exploration, sentiment analysis, and PostgreSQL integration, provided valuable insights into customer sentiments and potential connections between ratings and product categories.

# What’s included?
Within this repo you will find in the Starter_Files folder our Jupyter Notebook code named M_Daubenspeck_and_T_Elliott.ipynb, as well as our resources folder. Within the Resources folder you will find the campaign.csv, the category.csv, the contacts.csv, the contacts.xlsx, the crowdfunding.xlsx, the subcategory.csv, as well as our crowdfunding_db_schema.sql file.

# Sources
https://sparkbyexamples.com/pandas/pandas-set-order-of-columns-in-dataframe/
https://stackoverflow.com/questions/19632075/how-to-read-file-with-space-separated-values-in-pandas
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop.html
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.merge.html
https://www.geeksforgeeks.org/change-data-type-for-one-or-more-columns-in-pandas-dataframe/
https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html
https://stackoverflow.com/questions/20763012/creating-a-pandas-dataframe-from-a-numpy-array-how-do-i-specify-the-index-colum
https://pandas.pydata.org/docs/reference/api/pandas.Series.str.split.html
