# Using PySpark to Perform Linear Regression on Tips Data

This notebook shows how to use PySpark to perform linear regression on a tips dataset. The dataset is assumed to be stored in DBFS (Databricks File System), and it is read into a Spark DataFrame. The notebook then shows how to handle categorical features using PySpark's StringIndexer, assemble features using VectorAssembler, and perform linear regression using PySpark's LinearRegression.

## Getting Started
To run this notebook, you need to have access to a Spark cluster and a DBFS account. You also need to have the tips dataset in CSV format stored in DBFS.

## Prerequisites
The following software is required to run this notebook:
- Apache Spark
- PySpark
- Jupyter Notebook

## Running the Notebook
1. Start Jupyter Notebook and open the notebook file.
2. Update the `file_location` variable to the location of the tips dataset in DBFS.
3. Run each cell in the notebook to perform the following steps:
   - Read the tips dataset into a Spark DataFrame.
   - Handle categorical features using PySpark's StringIndexer.
   - Assemble features using PySpark's VectorAssembler.
   - Perform linear regression using PySpark's LinearRegression.
   - Print the mean absolute error and mean squared error of the model.
4. Analyze the results and modify the notebook as needed.

## Authors
Aloukik Aditya - [GitHub](https://github.com/aloukikaditya)

## Acknowledgments
This notebook is based on the Databricks documentation.
