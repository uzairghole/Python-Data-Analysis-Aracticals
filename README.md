# 📊 Python Data Analysis & Visualization

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge\&logo=python)
![NumPy](https://img.shields.io/badge/NumPy-1.x-013243?style=for-the-badge\&logo=numpy)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge\&logo=pandas)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557c?style=for-the-badge\&logo=matplotlib)

A collection of **Python Data Analysis, NumPy, Pandas, Data Wrangling, Exploratory Data Analysis (EDA), and Data Visualization projects** designed to build practical data analytics skills.

This repository contains beginner-to-intermediate projects using both **synthetic and real-world datasets**, with a focus on understanding data, manipulating it efficiently, and presenting meaningful insights through visualizations.

---

## 📌 Project Overview

The goal of this repository is to develop a strong foundation in Python-based data analysis.

The projects cover:

* 🐍 Python programming for data analysis
* 🔢 NumPy arrays and numerical operations
* 🐼 Pandas Series and DataFrames
* 🧹 Data cleaning and data wrangling
* 📊 Data visualization with Matplotlib
* 🔍 Exploratory Data Analysis (EDA)
* 📈 Statistical summaries and aggregation
* 📁 CSV data handling

---

## 📁 Projects Included

| #  | Project                          | Description                                                                                           | Main Concepts                |
| -- | -------------------------------- | ----------------------------------------------------------------------------------------------------- | ---------------------------- |
| 01 | **Histogram Visualization**      | Generates 1,000 normally distributed exam scores and visualizes their distribution using a histogram. | NumPy, Histogram, Matplotlib |
| 02 | **Trigonometric Plotting**       | Plots Sine and Cosine functions across a range of values.                                             | NumPy, Matplotlib            |
| 03 | **NumPy Fundamentals**           | Demonstrates array creation, dimensions, data types, shapes, and reshaping.                           | NumPy Arrays                 |
| 04 | **Slicing & Boolean Masking**    | Demonstrates 2D indexing, slicing, fancy indexing, and Boolean filtering.                             | Indexing, Masking            |
| 05 | **Pandas DataFrame Essentials**  | Introduces DataFrame creation, Series selection, inspection, and descriptive statistics.              | Pandas                       |
| 06 | **Data Wrangling & Aggregation** | Performs filtering, sorting, calculated columns, grouping, and aggregation.                           | `groupby()`, `sort_values()` |
| 07 | **Retail Sales Exploration**     | Performs initial EDA on retail sales data loaded from a CSV file.                                     | CSV, EDA, Pandas             |

---

## 🧮 01. Histogram Visualization

Generates **1,000 normally distributed exam scores** with:

* Mean (`μ`) = 70
* Standard deviation (`σ`) = 10
* 17 histogram bins

The project also displays a reference line representing the calculated mean.

**Technologies:**

`NumPy` • `Matplotlib`

---

## 📈 02. Trigonometric Plotting

Visualizes mathematical functions using NumPy and Matplotlib.

### Functions

* `sin(x)`
* `cos(x)`

The graph includes:

* Axis labels
* Title
* Legend
* Grid
* Multiple plotted functions

---

## 🔢 03. NumPy Fundamentals

Covers the fundamentals of NumPy arrays.

### Topics

* Array creation
* `zeros()`
* `ones()`
* `arange()`
* `linspace()`
* `reshape()`
* `shape`
* `ndim`
* `dtype`
* 1D and 2D arrays

Example transformation:

```text
1D Array
   ↓
12 Elements
   ↓
reshape(3, 4)
   ↓
3 × 4 Matrix
```

---

## ✂️ 04. Slicing & Boolean Masking

Demonstrates how to access and filter NumPy data efficiently.

### Topics

* Array indexing
* Row selection
* Column selection
* Slicing
* Fancy indexing
* Boolean conditions
* Data filtering

Example:

```python
filtered = arr[arr > 50]
```

This selects values greater than `50`.

---

## 🐼 05. Pandas DataFrame Essentials

Introduces the core concepts of Pandas DataFrames.

### Topics

* Creating DataFrames
* Creating Series
* Selecting columns
* Inspecting data
* Checking dimensions
* Data types
* Statistical summaries

Useful methods:

```python
df.shape
df.dtypes
df.head()
df.tail()
df.info()
df.describe()
```

---

## 🧹 06. Data Wrangling & Aggregation

Demonstrates practical data manipulation techniques.

### Operations Covered

* Filtering rows
* Sorting data
* Creating calculated columns
* Removing columns
* Renaming columns
* Grouping data
* Aggregating values

Important Pandas methods:

```python
df.sort_values()
df.groupby()
df.drop()
df.rename()
df.mean()
df.sum()
```

---

## 🛒 07. Retail Sales Exploration

Performs an initial **Exploratory Data Analysis (EDA)** on retail sales data stored in a CSV file.

### Workflow

```text
CSV Dataset
     ↓
Load Data
     ↓
Inspect Structure
     ↓
Check Data Types
     ↓
Descriptive Statistics
     ↓
Identify Data Quality Issues
     ↓
EDA
```

### Main Pandas Commands

```python
import pandas as pd

df = pd.read_csv("retail_store_sales.csv")

df.head()
df.info()
df.describe()
df.shape
df.dtypes
```

---

# 🛠️ Tech Stack

### Programming Language

🐍 **Python 3.x**

### Libraries

| Library       | Purpose                                    |
| ------------- | ------------------------------------------ |
| 🔢 NumPy      | Numerical computing and array manipulation |
| 🐼 Pandas     | Data analysis and data manipulation        |
| 📊 Matplotlib | Data visualization                         |

### Development Environments

* Anaconda Spyder
* VS Code
* Jupyter Notebook

---

# 💡 Key Concepts Covered

## 🔢 NumPy

* Array creation
* Array dimensions
* `shape`
* `ndim`
* `dtype`
* Reshaping
* Slicing
* Fancy indexing
* Boolean masking
* Mathematical operations
* Random data generation

## 🐼 Pandas

* Series
* DataFrames
* CSV files
* Data inspection
* Filtering
* Sorting
* Grouping
* Aggregation
* Column creation
* Column deletion
* Descriptive statistics

## 📊 Matplotlib

* Line plots
* Histograms
* Multiple plots
* Titles
* Labels
* Legends
* Gridlines
* Reference lines
* Plot customization

## 🔍 Exploratory Data Analysis

* Dataset inspection
* Data types
* Dataset dimensions
* Statistical summaries
* Missing-value investigation
* Data quality checks
* Data distribution

---

# 🚀 Getting Started

## Prerequisites

Make sure Python 3.x is installed.

Check your Python version:

```bash
python --version
```

or:

```bash
python3 --version
```

---

## 📦 Install Dependencies

Install the required libraries:

```bash
pip install numpy pandas matplotlib
```

If you are using Anaconda:

```bash
conda install numpy pandas matplotlib
```

---

# ▶️ Running the Projects

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/python-data-analysis-projects.git
```

Move into the project directory:

```bash
cd python-data-analysis-projects
```

Run any Python file:

```bash
python filename.py
```

For Jupyter Notebook:

```bash
jupyter notebook
```

---

# 📂 Suggested Project Structure

```text
python-data-analysis-projects/
│
├── README.md
├── requirements.txt
│
├── 01_histogram_visualization/
│   └── histogram.py
│
├── 02_trigonometric_plotting/
│   └── trigonometric.py
│
├── 03_numpy_fundamentals/
│   └── numpy_fundamentals.py
│
├── 04_slicing_masking/
│   └── slicing_masking.py
│
├── 05_pandas_dataframe/
│   └── dataframe.py
│
├── 06_data_wrangling/
│   └── data_wrangling.py
│
└── 07_retail_sales_eda/
    ├── retail_sales.py
    └── retail_store_sales.csv
```

---

# 📋 Requirements

Create a `requirements.txt` file containing:

```text
numpy
pandas
matplotlib
```

Then install everything with:

```bash
pip install -r requirements.txt
```

---

# 🎯 Learning Objectives

By completing these projects, you will gain practical experience with:

* Python for data analysis
* NumPy numerical computing
* Pandas data manipulation
* CSV dataset handling
* Data cleaning fundamentals
* Data aggregation
* Exploratory Data Analysis
* Data visualization
* Statistical interpretation
* Real-world data analysis workflows

---

# 📊 Learning Roadmap

```text
Python
  ↓
NumPy
  ↓
Pandas
  ↓
Data Wrangling
  ↓
Exploratory Data Analysis
  ↓
Matplotlib
  ↓
Data Visualization
  ↓
Real-World Data Projects
```

---

# 🌟 Future Improvements

Planned additions to this repository:

* [ ] Seaborn visualization projects
* [ ] Advanced Pandas projects
* [ ] Missing-value handling
* [ ] Advanced data cleaning
* [ ] Correlation analysis
* [ ] Statistical analysis
* [ ] More real-world datasets
* [ ] Interactive visualizations
* [ ] Machine Learning projects
* [ ] Complete EDA projects
* [ ] Dashboard projects

---

# 📚 What I Am Learning

This repository represents my practical learning journey in:

**Python → NumPy → Pandas → Data Wrangling → EDA → Data Visualization → Data Analytics**

Each project is designed to improve my understanding through hands-on implementation.

---

# 👨‍💻 Author

**Uzair Ghole**

Python • Data Analysis • NumPy • Pandas • Data Visualization

---

## ⭐ Support

If you find this repository useful, consider giving it a ⭐ on GitHub.

More Python and Data Analytics projects will be added as the learning journey continues.
