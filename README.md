# 🔥 Forest Fires in Brazil — Pandas Data Analysis

This project is a **Python Pandas data analysis project** based on the **Forest Fires in Brazil** dataset.

The main purpose of this project is to practice data cleaning, data manipulation, aggregation, and exploratory data analysis using Pandas.

## 📊 Dataset

The dataset contains information about forest fires reported in different states of Brazil.

The main columns used in the analysis include:

* `date`
* `month`
* `year`
* `state`
* `number`

The dataset is stored in:

```text
amazon.csv
```

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* Google Colab
* Jupyter Notebook

## 📁 Project Structure

```text
pandas-project-forest-fires-in-Brazil/
│
├── amazon.csv
├── forest fires in Brazil.ipynb
└── README.md
```

## 🔍 Analysis Performed

The notebook contains the following analysis:

### 1. Dataset Inspection

* Display the first 5 rows
* Display the last 5 rows
* Find the number of rows and columns
* Check column data types
* Get general information about the dataset
* Get statistical information using `describe()`

### 2. Data Cleaning

* Check for duplicate records
* Remove duplicate records
* Check for missing/null values
* Convert the `date` column to a datetime format
* Convert Portuguese month names into English abbreviations

For example:

```text
Janeiro   → Jan
Fevereiro → Feb
Março     → Mar
Abril     → Apr
...
Dezembro  → Dec
```

### 3. Forest Fire Analysis

The project analyzes:

* Total number of registered fire records
* Month with the highest number of reported fires
* Year with the highest number of reported fires
* State with the highest number of reported fires
* Total number of fires reported in Amazonas
* Year-wise fires reported in Amazonas
* Day-wise fires reported in Amazonas
* Monthly fire statistics for the year 2015
* Average number of fires by state
* States where fires were reported during December

## 📈 Pandas Operations Used

Some of the main Pandas operations used in this project are:

```python
data.head()
data.tail()
data.shape
data.info()
data.duplicated()
data.drop_duplicates()
data.isnull().sum()
data.describe()
data.groupby()
data.sort_values()
data.unique()
data.map()
data.sum()
data.mean()
```

These operations were used to inspect, clean, transform, group, and analyze the dataset.

## 🎯 Project Objective

The objective of this project is to understand how Pandas can be used to work with a real-world dataset.

Through this project, I practiced:

* Data inspection
* Data cleaning
* Handling duplicate data
* Checking missing values
* Data transformation
* GroupBy operations
* Sorting data
* Aggregation using `sum()` and `mean()`
* Date/time operations
* Extracting useful information from a dataset

## 📓 Notebook

The complete analysis is available in:

```text
forest fires in Brazil.ipynb
```

The notebook contains the step-by-step Pandas analysis and the corresponding outputs.

## 🚀 How to Run

1. Clone this repository.
2. Open `forest fires in Brazil.ipynb` using Google Colab or Jupyter Notebook.
3. Make sure `amazon.csv` is available.
4. Run the notebook cells from top to bottom.

> **Note:** The notebook currently uses Google Drive paths for loading the CSV file. If you run it on another computer or environment, update the CSV file path accordingly.

## 👨‍💻 Author

**Ashiq5172**

This project was created as part of my learning journey in **Python, Pandas, and Data Analysis**.
