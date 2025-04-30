# Air-Quality-and-Pollution-Data-Project
Exploratory Data Analysis and Database Creation on the UK Daily Air Quality Index Dataset

Due to Github's file size limits, the full dataset is hosted externally: (https://drive.google.com/file/d/1dUGRwmQdYH-OTdV4RhrzMezZOhg8IrPW/view?usp=sharing)

Also, due to Github's file size limits, the SQL database (Pollution_db2) created is hosted externally: (https://drive.google.com/file/d/1aFrgTg1WCYZXPiQ_FYz7ScDoy9wGOphh/view?usp=sharing)


**Project Overview**

This project involves processing, cleaning, and inserting air quality measurement data into a structured MySQL database. The goal is to create an efficient pipeline for handling environmental data, enabling future analysis and visualization.

The dataset used was originally sourced from a cleaned CSV file containing air pollution metrics across various UK monitoring sites.

**Key Objectives**

Build a relational database (MySQL) from raw air quality data.

Ensure robust handling of missing data (NaN → NULL replacements).

Perform optimized batch inserts for efficient database population.

Prepare the data for further analysis and dashboarding (e.g., Tableau, Power BI).

**Technologies Used**

Python (pandas, numpy, pymysql, json, xml.etree.ElementTree)

MySQL (database design and management)

Xampp and phpmyadmin (SQL database hosting)

Jupyter Notebook (development environment)

GitHub (project hosting)

**Installation & Setup**

Install Python and required libraries

Ensure MySQL is installed and running on localhost (via Xampp and http://localhost/phpmyadmin)

Run the 'Air_pollution_codes.ipynb' to create and populate the database.

**Key Highlights**

Handled missing values correctly to avoid SQL errors.

Used batch insertion techniques to improve data loading speed.

Maintained database normalization (separate tables for Sites, Instruments, and Measurements).

Sampled 86,000 rows to ensure reproducibility (random_state=42).

**Future Enhancements**

Build dynamic dashboards using Power BI or Tableau.

Perform exploratory data analysis (EDA) on air quality trends.

Automate ETL workflows using Apache Airflow.

**Author**

Sopuruchukwu Maryremigius Nwaeze
[MSc. Data Science - University of West England, Bristol]
