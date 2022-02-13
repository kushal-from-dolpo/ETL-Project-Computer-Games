# ETL-Project-Computer-Games

In this project, I extracted, transformed and loaded the video games sales data from VGChartz; and used that data to analyze and answer questions like most popular video games across each region, genre, console, etc. using SQL.

## Extract, Transfrom and Load

-Used Beautiful Soup, Splinter and pandas web scraping to write a python script to scrape games data from vgchartz and stored it as a csv file

-Deleted games without sales data, removed unwanted columns, added release year column, converted Release date values to date format and Sales values to float format and extracted the clean dataset as a csv file

-Designed the database tables in normalized form and generated ERD, created a SQL script for table creation in PostgreSQL and wrote a Jupyter notebook python script to split the transformed video games data into multiple dataframes and loaded them into PostgreSQL Database tables

## Data Analysis

-Wrote SQL queries to find out the most popular video games across different regions, console, genre, etc as well as most popular console across each regions. Also wrote SQL queries to determine which year was the sales highest in different regions.
