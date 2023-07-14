# Mini Project 2: Building an ETL pipeline

## Background

We (Gabrielle Bedewi, Max Glasser, and Joel Wiseman) partnered to practice building an ETL pipeline using Python, Pandas, and then used Python dictionary methods and regular expressions to extract and transform the data.  After transforming the data we created four CSV files and used the CSV file data to create an ERD and a table schema.  We then uploaded the CSV file data into a Postgres database.

### Before opening the starter code in Jupyter Notebook

1. We created a new repository in GitHub for this project called `Crowdfunding_ETL`. 
2. Inside the new repository we cloned the new repository to our computers.
3. Inside our local Git repository, we added and renamed the Jupitor notebook starter code ETL_Mini_Project_starter_code.ipynb to ETL_Mini_Project_GBedewi_MGlasser_JWiseman.ipynb.
4. We then added the Resources folder containing the crowdfunding.xlsx and contacts.xlsx.

## Part 1 - Created Dataframes then extracted and transformed the data

1. Created the Category and Subcategory DataFrames.
2. Created the Campaign DataFrame.
3. Created the Contacts DataFrame.
4. Extracted and transformed the data using Python dictionary methods (Python list comprehension) and using regular expressions.
5. Stored the extracted data as CSV files in the Resources folder.
    
## Part 2 - Created the Crowdfunding Database

1. Inspected the 4 CSV files (category.csv,subcategory.csv,contacts.csv, and campaign.csv), then sketched an ERD of the tables by using sqlflow.gudusoft.com
2. Used the information from the ERD to create the table schema for each CSV file.  Our instructor, Ms. Kalika, also provided us with the schema sql code for creating the tables. 
3. Saved the database schema as a Postgres file named PostgreSQL code.sql.
4. Created a new Postgres database, named Crowdfunding_db.
5. Used the database schema, and created the tables in the correct order (campaign table was last) to handle the foreign keys.
6. Verified the table creation by running a SELECT statement for each table.
7. Imported each CSV file into its corresponding SQL table.
8. Verified that each table had the correct data by running a SELECT statement for each.

## References

* Data for this dataset was generated by edX Boot Camps LLC, and is intended for educational purposes only.
