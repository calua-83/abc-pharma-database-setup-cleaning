# abc-pharma-database-setup-cleaning
A comprehensive repository for setting up and cleaning the ABC Pharmaceutical database. It includes scripts and tools for database initialization, data cleaning ensuring accurate and efficient data management for pharmaceutical applications.

## Contents

1. [Project Overview](#project-overview)
2. [Database Setup](#database-setup)
3. [Data Cleaning](#data-cleaning)
   

### Project Overview 

This project utilizes a pharmacy sales dataset to achieve the following:

 - Develop a normalized database structure with clearly defined dimension and fact tables.
 - Perform data cleaning to ensure accuracy, including handling null values and resolving spelling inconsistencies.
 - Create an ER diagram to illustrate the relationships between entities.

 ## Database Setup
This project involves creating a normalized database. The setup includes the following:

### Fact Tables
- **Sales Facts**: Contains transactional data like sales amounts, product IDs, and timestamps.

### Dimension Tables
- **Products Dimension**: Includes product details such as names, categories, and prices.
- **Customers Dimension**: Contains customer information like demographics and locations.
- **Time Dimension**: Stores date and time attributes for analysis.

SQL scripts for creating these tables and their relationships are detailed in the notebook.
