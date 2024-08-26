# LinkedIn-Data-Mart
Ingesting And Building LinkedIn Data Marts (ETL)
Project Overview
This project focuses on the extraction, transformation, and loading (ETL) of LinkedIn profile data into a data mart, followed by the visualization of the processed data using Tableau. The project aims to streamline LinkedIn profile data management by creating a structured SQL database from JSON data extracted via API. The final product is a comprehensive and interactive Tableau dashboard that enables users to explore and analyze LinkedIn profile data effectively.

Table of Contents
Project Overview
Architecture
Technologies Used
Dataset
ETL Pipeline
Extraction
Transformation
Loading
Database Schema
Tableau Visualizations
Final Dashboard
Setup and Execution
Future Work
Contributors
Architecture
The project is divided into three main stages:

ETL Pipeline:

Extraction: Extract LinkedIn profile data and pictures in JSON format via API.
Transformation: Normalize the extracted data, applying over 10 transformations to parse the JSON into structured SQL tables.
Loading: Store the processed data into an SQL database.
Data Mart:

The SQL database is used as a data mart for LinkedIn profile information.
Visualization:

The SQL database is imported into Tableau to create over 10 visualizations, culminating in a comprehensive dashboard with interactive search filters.
Technologies Used
Pentaho ETL: For data extraction, transformation, and loading processes.
SQL: For data storage and normalization.
Tableau: For data visualization and dashboard creation.
JSON: For data extraction via API.
Dataset
The dataset consists of LinkedIn profile data, including user details, job experiences, education, skills, and profile pictures, all in JSON format.

ETL Pipeline
Extraction
Source: LinkedIn API
Data Format: JSON
Process: Extracted LinkedIn profile data and pictures using the LinkedIn API.
Transformation
Normalization: Parsed and transformed the JSON data into normalized SQL tables.
Transformations: Applied over 10 transformations to ensure data integrity, remove redundancies, and prepare the data for loading into SQL.
Tools: Used Pentaho ETL for managing the transformation processes.
Loading
Destination: SQL Database
Process: Loaded the transformed data into the SQL database, ensuring it is structured for efficient querying and analysis.
Database Schema
The database schema is designed to handle normalized data efficiently. Below is a simplified schema overview:

Users: Stores general profile information.
Experiences: Stores job experiences linked to users.
Education: Stores educational background linked to users.
Skills: Stores skills associated with users.
Profile_Pictures: Stores links to user profile pictures.
The detailed schema can be explored in the attached SQL file (dump_group_11.sql).

Tableau Visualizations
After the ETL process, the SQL database was imported into Tableau, where the following visualizations were created:

Profile Summary: Overview of LinkedIn profiles.
Job Experience Analysis: Visual breakdown of job experiences.
Education Analysis: Insights into the educational background.
Skills Distribution: Analysis of skills across profiles.
Profile Picture Distribution: Distribution of profile pictures.
(Include a brief description for each visualization you created.)

Final Dashboard
The final Tableau dashboard combines all the visualizations into an interactive user interface. Key features include:

Interactive Search Filter: Allows users to search profiles based on various criteria such as job title, skills, education, etc.
Drill-Down Capabilities: Users can click on elements to see more detailed information.
Dynamic Updates: The dashboard updates automatically based on the filter criteria.
Setup and Execution
Prerequisites
Pentaho ETL
SQL Database (e.g., MySQL, PostgreSQL)
Tableau Desktop
LinkedIn API Access
