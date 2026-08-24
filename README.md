Bilkul 👍 Aapke diye hue **Histogram + Trigonometric Functions + NumPy + Pandas + Retail Sales Data Cleaning** code ko same style mein ek proper beginner-friendly README mein organize kar sakte ho.

# 📊 Python Data Analysis Basics

<p align="center">

<h3 align="center">🐍 Learning Python for Data Analysis</h3>

<p align="center">
A beginner-friendly collection of NumPy, Pandas, Matplotlib, and Seaborn concepts, examples, and practice programs.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/NumPy-2.x-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/Matplotlib-3.x-11557C?style=for-the-badge" alt="Matplotlib">
  <img src="https://img.shields.io/badge/Seaborn-0.13+-4C72B0?style=for-the-badge" alt="Seaborn">
  <img src="https://img.shields.io/badge/Level-Beginner-00C853?style=for-the-badge" alt="Level">
  <img src="https://img.shields.io/badge/Status-Learning-FF9800?style=for-the-badge" alt="Status">
</p>

---

## 📌 About

This repository contains my **Python Data Analysis learning and practice code**.

The main purpose of this project is to understand the fundamentals of:

* 🔢 NumPy
* 🐼 Pandas
* 📊 Matplotlib
* 🎨 Seaborn
* 🧹 Data Cleaning
* 📈 Data Visualization

I am practicing these concepts step-by-step using simple examples and real-world datasets.

### 🎯 Learning Goal

```text
Python
   ↓
NumPy
   ↓
Pandas
   ↓
Data Cleaning
   ↓
Data Visualization
   ↓
Data Analysis
   ↓
Machine Learning
```

---

# 📚 Table of Contents

* [✨ Features](#-features)
* [🛠️ Requirements](#️-requirements)
* [🚀 Installation](#-installation)
* [📖 Topics Covered](#-topics-covered)
* [🔢 NumPy Basics](#-1-numpy-basics)
* [🎯 NumPy Indexing](#-2-numpy-indexing)
* [🔍 Boolean & Fancy Indexing](#-3-boolean--fancy-indexing)
* [📊 Histogram](#-4-histogram)
* [📐 Trigonometric Functions](#-5-trigonometric-functions)
* [🐼 Pandas Basics](#-6-pandas-basics)
* [🔎 Pandas Filtering & Sorting](#-7-pandas-filtering--sorting)
* [📈 GroupBy & Aggregation](#-8-groupby--aggregation)
* [📂 Loading CSV Data](#-9-loading-csv-data)
* [🧹 Data Inspection](#-10-data-inspection)
* [🧼 Missing Values](#-11-missing-values)
* [🧹 Data Cleaning](#-12-data-cleaning)
* [🧠 What I Learned](#-what-i-learned)
* [🛣️ Learning Roadmap](#️-learning-roadmap)
* [📁 Project Structure](#-project-structure)
* [🎯 Why Learn Data Analysis](#-why-learn-data-analysis)
* [🚀 Future Plans](#-future-plans)
* [📈 My Learning Journey](#-my-learning-journey)

---

# ✨ Features

This repository demonstrates:

* 🔢 Creating NumPy arrays
* 📐 NumPy array properties
* 🔄 Reshaping arrays
* 🎯 Positive and negative indexing
* ✂️ Array slicing
* 🔍 Boolean indexing
* 🎯 Fancy indexing
* 📊 Statistical calculations
* 📈 Histogram visualization
* 📐 Trigonometric functions
* 🐼 Creating Pandas DataFrames
* 📋 Working with Pandas Series
* 🔎 Filtering DataFrames
* 🔃 Sorting data
* ➕ Creating new columns
* 📊 GroupBy and aggregation
* 📂 Reading CSV datasets
* 🔍 Data inspection
* ❌ Detecting missing values
* 🔁 Detecting duplicate records
* 🧹 Basic data cleaning

---

# 🛠️ Requirements

Before running the project, make sure you have:

* 🐍 Python 3.x
* 🔢 NumPy
* 🐼 Pandas
* 📊 Matplotlib
* 🎨 Seaborn
* 💻 VS Code / Jupyter Notebook / PyCharm

---

# 🚀 Installation

## 1️⃣ Clone the Repository

```bash
git clone <your-repository-url>
```

## 2️⃣ Open the Project

```bash
cd python-data-analysis
```

## 3️⃣ Install Required Libraries

```bash
pip install numpy pandas matplotlib seaborn
```

Or install using `requirements.txt`:

```bash
pip install -r requirements.txt
```

## 4️⃣ Run the Program

```bash
python data_analysis.py
```

---

# 📖 Topics Covered

|  #  | Topic                | Concepts                       |
| :-: | -------------------- | ------------------------------ |
|  01 | 🔢 NumPy Basics      | Arrays & Array Properties      |
|  02 | 🎯 NumPy Indexing    | Positive & Negative Indexing   |
|  03 | 🔍 Advanced Indexing | Boolean & Fancy Indexing       |
|  04 | 📊 Histogram         | Distribution & Frequency       |
|  05 | 📐 Trigonometry      | `sin()`, `cos()`, `linspace()` |
|  06 | 🐼 Pandas Basics     | DataFrame & Series             |
|  07 | 🔎 Data Filtering    | Conditions & Sorting           |
|  08 | 📈 GroupBy           | Aggregation & Mean             |
|  09 | 📂 CSV Loading       | `read_csv()`                   |
|  10 | 🔍 Data Inspection   | `info()`, `describe()`         |
|  11 | ❌ Missing Values     | `isnull()`                     |
|  12 | 🧹 Data Cleaning     | Drop, Rename & Duplicates      |

---

# 🔢 1. NumPy Basics

NumPy is used for numerical computing and working with arrays in Python.

## Creating Arrays

```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])

b = np.zeros((3, 3))

c = np.ones((2, 4))

d = np.arange(0, 10, 2)

e = np.linspace(0, 1, 5)

print(a)
print(b)
print(c)
print(d)
print(e)
```

### Array Properties

```python
print(a.shape)
print(a.dtype)
print(a.ndim)
```

| Property | Meaning              |
| -------- | -------------------- |
| `shape`  | Dimensions of array  |
| `dtype`  | Data type            |
| `ndim`   | Number of dimensions |

---

# 🔄 Reshaping

`reshape()` is used to change the shape of an array without changing its data.

```python
matrix = np.arange(12).reshape(3, 4)

print(matrix)
```

Output:

```text
[[ 0  1  2  3]
 [ 4  5  6  7]
 [ 8  9 10 11]]
```

---

# 🎯 2. NumPy Indexing

Indexing is used to access individual elements from an array.

```python
import numpy as np

arr = np.array([10, 20, 30, 40, 50])

print(arr[0])
print(arr[-1])
print(arr[1:4])
```

Output:

```text
10
50
[20 30 40]
```

### 2D Indexing

```python
m = np.array([
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
])

print(m[1, 2])
print(m[:, 1])
print(m[0:2, :])
```

---

# 🔍 3. Boolean & Fancy Indexing

## Boolean Masking

Boolean indexing allows us to select elements based on a condition.

```python
scores = np.array([85, 42, 91, 67, 73])

passed = scores[scores >= 70]

print(passed)
```

Output:

```text
[85 91 73]
```

### Fancy Indexing

Fancy indexing allows us to select specific positions.

```python
idx = [0, 3, 4]

print(arr[idx])
```

Output:

```text
[10 40 50]
```

---

# 📊 4. Histogram

A histogram is used to visualize the distribution of numerical data.

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

data = np.random.normal(70, 10, 1000)

plt.hist(
    data,
    bins=17,
    edgecolor="gray",
    alpha=0.7,
    color="#FFFFFF"
)

plt.title("Exam Score Distribution")
plt.xlabel("Score")
plt.ylabel("Frequency")

plt.axvline(
    data.mean(),
    color="gray",
    linestyle="--",
    label="Mean"
)

plt.legend()
plt.show()
```

### Concepts Used

| Function             | Purpose                           |
| -------------------- | --------------------------------- |
| `np.random.normal()` | Generate normal-distribution data |
| `plt.hist()`         | Create histogram                  |
| `plt.axvline()`      | Draw vertical line                |
| `data.mean()`        | Calculate mean                    |

---

# 📐 5. Trigonometric Functions

NumPy provides mathematical functions such as:

* `sin()`
* `cos()`
* `tan()`

## Line Plot

```python
import matplotlib.pyplot as plt
import numpy as np

x = np.linspace(0, 10, 100)

plt.plot(x, np.sin(x), label="sin(x)")
plt.plot(x, np.cos(x), label="cos(x)")

plt.title("Trigonometric Functions")
plt.xlabel("x")
plt.ylabel("y")

plt.legend()
plt.grid(True)

plt.show()
```

This program creates a line plot showing the behavior of:

```text
sin(x)
cos(x)
```

---

# 🐼 6. Pandas Basics

Pandas is a Python library used for data manipulation and analysis.

## Creating a DataFrame

```python
import pandas as pd

df = pd.DataFrame({
    "Name": ["Alice", "Bob", "Charlie"],
    "Age": [25, 30, 35],
    "Score": [88.5, 92.3, 79.1]
})

print(df)
```

Output:

```text
      Name  Age  Score
0    Alice   25   88.5
1      Bob   30   92.3
2  Charlie   35   79.1
```

---

## Series

A single DataFrame column is a Pandas Series.

```python
ages = df["Age"]

print(type(ages))
```

---

## Quick Inspection

```python
print(df.shape)

print(df.dtypes)

print(df.describe())
```

### Important Functions

| Function     | Purpose                  |
| ------------ | ------------------------ |
| `shape`      | Number of rows & columns |
| `dtypes`     | Data types               |
| `describe()` | Statistical summary      |

---

# 🔎 7. Pandas Filtering & Sorting

```python
import pandas as pd

df = pd.DataFrame({
    "Name": ["Alice", "Bob", "Charlie", "Diana"],
    "Dept": ["IT", "HR", "IT", "HR"],
    "Salary": [70000, 65000, 80000, 72000]
})
```

## Filtering

### IT Department

```python
it_team = df[df["Dept"] == "IT"]

print(it_team)
```

### High Salary

```python
high_pay = df[df["Salary"] > 70000]

print(high_pay)
```

---

## Sorting

```python
sorted_df = df.sort_values(
    "Salary",
    ascending=False
)

print(sorted_df)
```

---

# ➕ Creating a New Column

A new column can be created using existing data.

```python
df["Bonus"] = df["Salary"] * 0.1

print(df)
```

Here:

```text
Bonus = Salary × 10%
```

---

# 📈 8. GroupBy & Aggregation

`groupby()` is useful for calculating statistics for different groups.

```python
dept_avg = df.groupby("Dept")["Salary"].mean()

print(dept_avg)
```

Example result:

```text
Dept
HR    68500
IT    75000
Name: Salary, dtype: float64
```

---

# 🗑️ Drop & Rename

## Drop Column

```python
df = df.drop(columns=["Bonus"])
```

## Rename Column

```python
df = df.rename(
    columns={
        "Dept": "Department"
    }
)
```

---

# 📂 9. Loading CSV Data

Real-world datasets are commonly stored in CSV files.

```python
import numpy as np
import pandas as pd

df = pd.read_csv("retail_store_sales.csv")

print(df)
```

---

# 🔍 10. Data Inspection

After loading a dataset, the first step is to inspect the data.

## Display Data

```python
print(df)
```

## Dataset Information

```python
df.info()
```

## Statistical Summary

```python
print(df.describe())
```

### Common Inspection Functions

| Function     | Purpose             |
| ------------ | ------------------- |
| `head()`     | First rows          |
| `info()`     | Dataset information |
| `describe()` | Statistical summary |
| `shape`      | Rows and columns    |
| `dtypes`     | Column data types   |

---

# ❌ 11. Missing Values

Missing values are common in real-world datasets.

## Check Missing Values

```python
print(df.isnull().mean())
```

## Missing Percentage

```python
print(df.isnull().mean() * 100)
```

This helps identify which columns contain missing data.

---

# 🔁 12. Duplicate Records

Duplicates can affect data analysis.

```python
print(df[df.duplicated()])
```

This returns rows that are duplicated.

---

# 🧹 Data Cleaning

Data cleaning is an important step before analysis.

```python
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn

df = pd.read_csv("retail_store_sales.csv")
```

## Basic Inspection

```python
print(df)

print(df.info())

print(df.describe())
```

## Missing Values

```python
print(df.isnull().mean())

print(df.isnull().mean() * 100)
```

## Check Duplicates

```python
print(df[df.duplicated()])
```

## Create Copy

```python
df1 = df.copy()
```

## View First 15 Rows

```python
print(df1.head(15))
```

## Remove Unnecessary Column

```python
df2 = df1.drop(
    columns=["Transaction ID"]
)

print(df2.head(15))
```

---

# 🧠 What I Learned

By completing these Python Data Analysis exercises, I practiced:

* ✅ Creating NumPy arrays
* ✅ Understanding array properties
* ✅ Reshaping NumPy arrays
* ✅ Positive and negative indexing
* ✅ Array slicing
* ✅ Boolean masking
* ✅ Fancy indexing
* ✅ Generating random data
* ✅ Creating histograms
* ✅ Plotting mathematical functions
* ✅ Using `sin()` and `cos()`
* ✅ Creating Pandas DataFrames
* ✅ Working with Pandas Series
* ✅ Inspecting datasets
* ✅ Filtering DataFrames
* ✅ Sorting data
* ✅ Creating new columns
* ✅ Using GroupBy
* ✅ Performing aggregation
* ✅ Loading CSV files
* ✅ Checking missing values
* ✅ Detecting duplicates
* ✅ Cleaning datasets
* ✅ Removing unnecessary columns

---

# 🛣️ Learning Roadmap

## ✅ Completed

* [x] NumPy Array Basics
* [x] Array Properties
* [x] Array Creation
* [x] Reshaping
* [x] Indexing
* [x] Slicing
* [x] Boolean Indexing
* [x] Fancy Indexing
* [x] Histogram
* [x] Trigonometric Functions
* [x] Pandas DataFrame
* [x] Pandas Series
* [x] Filtering
* [x] Sorting
* [x] GroupBy
* [x] CSV Loading
* [x] Data Inspection
* [x] Missing Value Checking
* [x] Duplicate Checking
* [x] Basic Data Cleaning

## 🔜 Next Topics

* [ ] NumPy Broadcasting
* [ ] NumPy Array Arithmetic
* [ ] Advanced NumPy Operations
* [ ] Pandas `loc` and `iloc`
* [ ] Handling Missing Values
* [ ] Removing Duplicates
* [ ] Merging DataFrames
* [ ] Joining DataFrames
* [ ] Pivot Tables
* [ ] Matplotlib Charts
* [ ] Seaborn Visualization
* [ ] Exploratory Data Analysis
* [ ] Real-World Data Analysis Projects
* [ ] Machine Learning

---

# 🛠️ Tech Stack

<p>
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/NumPy-2.x-013243?style=flat-square&logo=numpy&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-2.x-150458?style=flat-square&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Matplotlib-3.x-11557C?style=flat-square&logo=matplotlib&logoColor=white">
  <img src="https://img.shields.io/badge/Seaborn-0.13+-4C72B0?style=flat-square" alt="Seaborn">
  <img src="https://img.shields.io/badge/Editor-VS%20Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white">
</p>

---

# 📁 Project Structure

```text
python-data-analysis/
│
├── 🐍 data_analysis.py
├── 📄 README.md
├── 📦 requirements.txt
└── 📊 retail_store_sales.csv
```

### `data_analysis.py`

Contains NumPy, Pandas, Matplotlib, and data-cleaning practice programs.

### `README.md`

Contains documentation, concepts, examples, and learning notes.

### `requirements.txt`

Contains project dependencies.

```text
numpy
pandas
matplotlib
seaborn
```

### `retail_store_sales.csv`

Contains the retail sales dataset used for data analysis and cleaning practice.

---

# 🎯 Why Learn Data Analysis?

Python Data Analysis skills are useful for understanding and working with large datasets.

The learning path can be represented as:

```text
          Python
             │
             ▼
          NumPy
             │
             ▼
          Pandas
             │
             ▼
       Data Cleaning
             │
             ▼
     Data Visualization
             │
             ▼
      Exploratory Analysis
             │
             ▼
     Machine Learning
             │
             ▼
        Data Science
```

Python data analysis knowledge is useful when learning:

* 📊 Data Science
* 🤖 Machine Learning
* 📈 Business Intelligence
* 🧠 Artificial Intelligence
* 🔬 Scientific Computing
* 📉 Statistics

---

# 🚀 Future Plans

I will continue improving this repository by adding:

* 📚 More NumPy concepts
* 🐼 Advanced Pandas operations
* 📊 More visualization examples
* 🎨 Matplotlib projects
* 📈 Seaborn projects
* 🧹 Advanced data-cleaning techniques
* 📊 Exploratory Data Analysis projects
* 🧩 Mini data-analysis exercises
* 📂 More real-world datasets
* 🤖 Machine-learning-related projects

---

# 📈 My Learning Journey

```text
🐍 Python
    │
    ▼
🧮 NumPy
    │
    ▼
🐼 Pandas
    │
    ▼
🧹 Data Cleaning
    │
    ▼
📊 Matplotlib / Seaborn
    │
    ▼
📈 Data Analysis
    │
    ▼
🤖 Machine Learning
    │
    ▼
🧠 Data Science
```

---

## ⭐ Progress

```text
Python              ████████████████████ 100%
NumPy               ███████████████████  90%
Pandas              ████████████████     75%
Data Cleaning       ██████████████       65%
Visualization       ████████████         60%
Data Analysis       █████████            45%
Machine Learning    ████                 20%
```

---

<p align="center">
  ⭐ Keep Learning • Keep Practicing • Keep Building ⭐
</p>

<p align="center">
  🐍 Python → 🧮 NumPy → 🐼 Pandas → 📊 Data Analysis → 🤖 Machine Learning
</p>
