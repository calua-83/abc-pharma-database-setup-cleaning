# abc-pharma-database-setup-cleaning
A comprehensive repository for setting up and cleaning the ABC Pharmaceutical database. It includes scripts and tools for database initialization, data cleaning ensuring accurate and efficient data management for pharmaceutical applications.


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
## Key Features
- **Data Cleaning**: Handled null values, standardized spelling inconsistencies, and ensured data integrity.
- **Database Normalization**: Structured data into dimension and fact tables for efficient querying.
- **Visualization**: Created an Entity-Relationship (ER) diagram to represent database relationships.
- **Transformation Logic**: Applied transformations to meet analytical requirements.

## Notebook Contents
This repository includes the Jupyter Notebook file with:
- Detailed step-by-step transformation logic.
- Python code for data cleaning and manipulation.
- Markdown cells explaining the rationale behind each step.

## Getting Started
1. Clone the repository.
2. Install the necessary dependencies (`requirements.txt` if available).
3. Run the notebook using Jupyter Notebook or JupyterLab.

## How to Use
1. Open the notebook file: `ABC Pharm Data Transformation.ipynb`.
2. Follow the provided markdown explanations and run the code cells sequentially.
3. Review the transformed data and ER diagram for insights.

## Requirements
- Python 3.x
- Jupyter Notebook
- Required Python libraries (e.g., Pandas, NumPy, Matplotlib).
- SQLITE

 ## Entity-Relationship (ER)
