# Mudano_Data_Engineer_Assignment

This assignment involved analysing publicly available World Bank data using two datasets: one containing country information and the second dataset including GDP data.

The Pandas package was used to import and clean the data prior to data analysis. This was done by concatenating the datasets on the ISO country codes and by removing any unnecessary columns not required for this analysis. The dataset was then exported as a CSV file and then stored in a PostgreSQL local database to query the data via SQL.

This repository includes the Jupyter Notebook used to import the initial datasets and export the final dataset for querying. Please see the SQL scripts for each question in this assignment as well as the script used to create the table in PGAdmin 4 in the 'SQL scripts' folder. You can find more details of the results of the assignment questions in the 'Assignment Details.docx' file.
