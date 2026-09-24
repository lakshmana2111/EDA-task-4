# 📈 Task 4 - Shopify Stock Data Analysis

## 📌 Project Overview

This project performs **Exploratory Data Analysis (EDA)** on Shopify stock market data using Python.

The analysis focuses on understanding:

* Shopify stock price trends
* Opening, high, low, and closing prices
* Trading volume
* Moving averages
* Daily returns
* Distribution of daily returns

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

---

## 📂 Dataset

The dataset used in this project is:

```text
shopify_stock.csv
```

The dataset contains Shopify stock market information such as:

* Date
* Open Price
* High Price
* Low Price
* Close Price
* Volume

---

# 🔍 Steps Performed

## Step 1 - Import Required Libraries

The required Python libraries are imported.

```python
import numpy as np
import pandas as pd
import seaborn as sns
import matplotlib.pyplot as plt
```

### Purpose

* **NumPy** - Numerical operations
* **Pandas** - Data loading and analysis
* **Matplotlib** - Data visualization
* **Seaborn** - Statistical visualization

---

## Step 2 - Load the Dataset

The Shopify stock dataset is loaded using Pandas.

```python
df = pd.read_csv("/content/shopify_stock.csv")
```

The dataset is stored in a DataFrame named `df`.

---

## Step 3 - Display the First Rows

The first few records are displayed using:

```python
df.head()
```

This helps to understand the structure and contents of the dataset.

---

## Step 4 - Display the Last Rows

The last few records are displayed using:

```python
df.tail()
```

This helps to check the ending records of the dataset.

---

## Step 5 - Check Dataset Shape

The number of rows and columns is checked using:

```python
df.shape
```

This provides the size of the dataset.

---

## Step 6 - Check Dataset Information

The structure and data types of the dataset are checked using:

```python
df.info()
```

This shows:

* Column names
* Number of entries
* Data types
* Non-null values

---

## Step 7 - Generate Statistical Summary

Descriptive statistics are generated using:

```python
df.describe()
```

This provides statistical information such as:

* Count
* Mean
* Standard deviation
* Minimum
* Maximum
* Quartiles

for the n
