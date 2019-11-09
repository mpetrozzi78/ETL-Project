# ETL-Project

The goal of this project is to analyse the data analyst job vacancies in the major US cities and compare the offered salaries witht the cost of living of that city.

I have web scraped Indeed website for data analyst jobs in major US cities.
I have also used a csv file found on Kaggle regarding the cost of living all around the world (https://www.kaggle.com/andytran11996/cost-of-living). Data was taken in 2017 from Numbeo.

After having the csv files, I read them in Jupyter Notebook and created dataframes about them. I cleaned the 2 dataframes up from duplicates and split columns when necessary. After having my final dataframes, I created a database on Postgres containing 2 tables: data_jobs and cost_living. 

I then connected the database in Jupyter notebook and called the 2 tables.

The data is now ready to be analyzed.


