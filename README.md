# Creating ETL Data Pipelines using Apache Airflow

## About This Repo

This repository aims to create data pipe ETL using Apache Airflow. This involves the work of setting up Apache Airflow, extracting data from various file formats, converting data, and loading data into the staging area.

## Objectives

In this repo, you will author an Apache Airflow DAG that will:

- Extract data from a CSV file
- Extract data from a TSV file
- Extract data from a TXT file fixed-width file
- Transform the data
- Load the transformed data into the staging area

## Implementation steps

Please follow the steps provided in the assignment document to complete the tasks. These include:

1. Setting up the lab environment.
2. Creating the necessary directory structure.
3. Saving the defined DAG into a Python file.
4. Submitting the DAG: copy the DAG into a Python file to \airflow\dags
5. Unpausing the DAG: => airflow dags unpause ETL_toll_data
6. Trigger DAG : => airflow dags trigger ETL_toll_data
6. Monitoring the DAG runs.
