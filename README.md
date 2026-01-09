# Car Price Analysis and Data Preprocessing (2010-2020)

This project performs data analysis, cleaning, and feature engineering on a dataset containing car information from the years 2010-2020 using **Python**.

## 📂 Project Overview

The following steps were implemented in this Jupyter Notebook:

1. **Exploratory Data Analysis (EDA):**
* Examining dataset dimensions, column names, and data types.
* Extracting basic statistical information (mean, standard deviation, min/max, etc.).
* Analyzing the distribution of vehicles by fuel type.


2. **Data Visualization:**
* Creating a histogram to visualize the distribution of vehicle prices using `matplotlib`.


3. **Missing Value Handling:**
* Simulating missing data (NaN) by randomly assigning null values to specific entries.
* Filling these missing values using the **Mode (most frequent value)** of the respective column.


4. **Data Manipulation & Feature Engineering:**
* Dropping columns deemed unnecessary for the analysis (`Model`).
* Creating a new `Size` column with random categorical data.
* Mapping categorical values (`Small`, `Medium`, `Large`) to numerical values (`1`, `2`, `3`).



## 🛠️ Technologies and Libraries

The following Python libraries are required to run this project:

* **Pandas:** For data frame manipulation and analysis.
* **NumPy:** For numerical operations and random data generation.
* **Matplotlib:** For data visualization (plotting).

## 🚀 Installation and Usage

1. Install the required libraries:
```bash
pip install pandas numpy matplotlib

```


2. Ensure that the `cars_2010_2020.csv` file is located in the same directory as the project notebook.
3. Open the Jupyter Notebook and execute the cells in order.

## 📊 Dataset Information

The dataset (`cars_2010_2020.csv`) contains the following columns:

* **Make:** Car brand
* **Model:** Car model (Dropped during analysis)
* **Year:** Manufacturing year
* **Engine Size (L):** Engine capacity in liters
* **Fuel Type:** Type of fuel (Petrol, Diesel, Hybrid, Electric)
* **Price (USD):** Price of the vehicle
