# Delta Lake Merge Implementation

## Overview

This project demonstrates incremental data processing using **Delta Lake** with **PySpark**. The implementation focuses on loading data into a Delta table, performing basic data cleaning, creating incremental data, applying the **MERGE** operation, and validating the final results.

## Objective

The objective of this assignment is to implement Delta Lake's MERGE functionality to efficiently update existing records and insert new records into a Delta table while maintaining data consistency.

## Dataset

The project uses the **Sample Superstore** dataset as the primary source of data. An additional incremental dataset is created to simulate newly arriving records for demonstrating incremental processing.

## Technologies Used

- Python
- PySpark
- Delta Lake
- Google Colab
- Pandas

## Tasks Performed

- Loaded the Superstore dataset into a Spark DataFrame.
- Explored the dataset and verified its schema.
- Checked for missing values.
- Checked for duplicate records.
- Renamed column names to make them compatible with Delta Lake.
- Stored the cleaned dataset as a Delta table.
- Created an incremental dataset containing updated and new records.
- Saved the incremental dataset as a CSV file.
- Performed the Delta Lake **MERGE** operation using `Order_ID` and `Product_ID` as matching keys.
- Updated matching records and inserted new records.
- Validated the results by verifying row counts and checking the updated and inserted records.
- Displayed the final merged dataset.

## Key Features

- Data validation before processing
- Delta Lake table creation
- Incremental data simulation
- MERGE operation for update and insert
- Result validation
- End-to-end implementation using PySpark

## Output

The project successfully demonstrates:

- Creation of a Delta table
- Incremental data processing
- Successful update of existing records
- Successful insertion of new records
- Validation of the final merged dataset

## Learning Outcomes

Through this assignment, I gained practical experience in:

- Working with Apache Spark DataFrames
- Using Delta Lake for reliable data management
- Performing incremental data processing
- Implementing the MERGE operation in Delta Lake
- Validating data quality using PySpark
- Building a complete data engineering workflow in Google Colab
