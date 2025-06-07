# ETL Process for HR Data

This project is an ETL process to help a company develop there recruiting strategies by synethising all data about data scientists who successfully pass some courses which conduct by the company from different sources.

## 🔍 Overview

The goal of this project is to:
- **Extract** data from various sources
- **Transform** the data using filtering, renaming, and cleaning
- **Load** the clean data into a final table for the company later analysis on their recruitment 


## 📁 Project Structure

- `ETL_Process.ipynb`: Jupyter Notebook containing the full ETL workflow.

## ⚙️ Technologies Used

- Python 3.x
- Pandas

## ▶️ How to Run

1. Open the notebook using [Google Colab](https://colab.research.google.com/) or any Jupyter environment.
2. Run each cell sequentially.
3. Review the intermediate outputs (extracted data, transformed data, and final loaded data).

## 📌 Key Steps in the Notebook

### 1. Extract
- Extracting data from 6 different databases:
  1. Enrollies Data - Google Docs
  2. Enrollies' Education - Excel file
  3. Enrollies Working Experience - CSV file
  4. Training Hours - SQL database
  5. City Development Index (CDI) - Websit
  6. Employment - MySQL database

### 2. Transform
- Transform columns' datatype into optimal types (e.g: object -> string, object -> category)
- Since most columns with missing values are categorical, "mode" function is used to fill missing values.

### 3. Load
- Creating a path to the completed database "data_warehouse.bd"


## 📜 License

This project is open-source and free to use. Add a license file if needed (e.g., MIT, Apache 2.0).
