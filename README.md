# Walmart Sales Data Analysis and Ad-Hoc Query Project
# Project Overview

This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. Using Python for data processing and analysis, PLSQL and MySQL for advanced querying, and structured problem-solving techniques, we address key business questions to help improve Walmart's operations.

This repository is ideal for data analysts aiming to develop skills in data manipulation, SQL querying, ad-hoc analysis and data pipeline creation.

# Project Steps

# 1.Set Up the Environment

* Tools Used: Visual Studio Code (VS Code), Python, SQL (MySQL and PostgreSQL)

* Goal: Create a structured workspace in VS Code, organizing project folders for smooth development and data handling.

# 2.Set Up Kaggle API

* API Setup: Obtain your Kaggle API token from Kaggle.

* Configure Kaggle:

      * Place the kaggle.json file in your local .kaggle folder.

      * Use the command kaggle datasets download -d <dataset-path> to download datasets.

# 3.Download Walmart Sales Data

* Data Source: Use Kaggle API to download the Walmart sales dataset.

* Storage: Save the data in the data/ folder for easy access.

# 4. Install Required Libraries and Load Data

* Install Libraries:

*pip install pandas numpy sqlalchemy mysql-connector-python psycopg2*

* Load Data: Read data into a Pandas DataFrame for analysis.

  # 5. Explore the Data

* Goal: Understand data distribution, column names, types, and identify potential issues.

* Techniques: Use .info(), .describe(), and .head() for initial exploration.

# 6. Data Cleaning

* Remove duplicates.

* Handle missing values by filling or dropping them as appropriate.

* Fix inconsistent data types (e.g., ensure dates are datetime, prices are float).

* Format currency values using .replace().

# 7. Feature Engineering

* Add a total_amount column by calculating unit_price * quantity.

* Enhance the dataset for SQL-based aggregation and analysis.

# 8. Load Data into MySQL and PostgreSQL

* Set Up Connections: Use SQLAlchemy to connect to MySQL and psycopg2 to connect PostgreSQL.

* Automate Table Creation: Load cleaned data into databases.

* Verify: Run initial SQL queries to confirm successful data insertion.

# 9. SQL Analysis: Complex Queries and Business Problem Solving

Answer critical business questions by writing and executing SQL queries.

# 10. Project Publishing and Documentation

* Maintain documentation in Markdown or Jupyter Notebooks.

* Publish the project on GitHub, including:

* README.md file

* SQL query scripts

* Data files or steps to access them

  # Requirements

* Python: 3.8+

* SQL Databases: MySQL, PostgreSQL

* Python Libraries:

      pandas, numpy, sqlalchemy, mysql-connector-python, psycopg2

* Kaggle API Key

  # Results and Insights

# Sales Insights

* Key categories and branches with highest sales.

* Preferred payment methods across branches.

# Profitability

* High-profit categories and locations.

# Customer Behavior

* Trends in ratings, payment preferences, and peak shopping hours.

# Project Directory Structure

Walmart-Data-Analysis/

├── data/

├── notebooks/

├── sql_queries/

├── README.md

├── requirements.txt


# How to Run

* Clone this repository.

* Install the required libraries using:

         pip install -r requirements.txt

* Set up Kaggle API and download the dataset.

* Follow the steps in the project to replicate the analysis.  



