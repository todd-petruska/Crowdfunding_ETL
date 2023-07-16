# Crowdfunding_ETL

Project Contributors: N.Tivakaran, T.Petruska, M.Enyew, and G.Kalad

Background:  This is a team ETL mini project focused on building an ETL (Extract, Transform, Load) pipeline using Python, Pandas, and SQL to extract and transform the data.  . The goal was to extract and transform data from crowdfunding.xlsx and contacts.xlsx files, create CSV files, generate an Entity Relationship Diagram (ERD), define a table schema, and upload the data into a Postgres database.

A repository labeled Crowdfunding_ETL-Project-2 contains the following files:
* Crowdfunding SQL Tables folder containing the following files:
*   QDB.png file (ERD) 
*   campaign_table_screenshot.png
*   category_table_screenshot.png
*   contacts_table_screenshot.png
*   subcategory_table_screenshot.png
*   crowdfunding_db_final.sql

*   ETL_Mini_Project_Starter_Code N.Tivakaran,T.Petruska,M.Enyew,G.Kalad.ipynb
*   Readme.md
*   Resources folder containing the following files: 
*   campaign.csv
*   category.csv
*   contacts.csv
*   campaign.xlsx
*   crowdfunding.xlsx
*   subcategory.csv

This project consists of the following subsections:
* Creates the Category and Subcategory DataFrames from the crowdfunding.xlsx file
* Creates the Campaign DataFrame with specific columns of interests, then exports the campaign file as a CSV. 
* Creates the Contacts DataFrame from the contacts.xlsx file, iterates through the DataFrame, converts each row into a dictionary, which is filtered, then exported as contacts.csv file.

* Creates the Crowdfunding Database from category.csv, subcategory.csv, contacts.csv, and campaign.csv from an ERD sketch, which creates schema for each of the respective csv files and specifies the data types, primary keys, foreign keys, and other constraints. The schema file is labeled crowdfunding_db_schema.sql.  The application pgAdmin4 is used to create a Postgres database called crowdfunding_db.  Tables are then ingested in this order: category.csv, subcategory.csv, contacts.csv, and campaign.csv to handle the foreign keys. 

Resources used for this project include, Instructor assistance during Office Hours, course material, course provided starter-code, collaboration with team members, instructor-provided SQL schema, AskBCS Learning Assistants, QuickDBD, Stack Overflow, Blackbox, Chat GPT, Creative Commons, Towards Data Science, Tutorials Point, and Geeks for Geeks.
