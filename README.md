Bilkul. Aapke **exact 9 points** ko follow karke README ko premium, clean aur GitHub-friendly bana raha hoon. Isme unnecessary emojis/repetition kam hai, aur code examples bhi compact hain.

# 🐍 Python Data Analysis

<p align="center">
  <img src="https://raw.githubusercontent.com/python/cpython/main/Doc/logo.png" width="90" alt="Python">
</p>

<h1 align="center">Python Data Analysis</h1>

<p align="center">
  <b>NumPy • Pandas • Matplotlib • Seaborn</b>
</p>

<p align="center">
  Learning data analysis through practical Python programs,
  visualization, data cleaning, and real-world datasets.
</p>

<p align="center">

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge\&logo=python\&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-2.x-013243?style=for-the-badge\&logo=numpy\&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2.x-150458?style=for-the-badge\&logo=pandas\&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-11557C?style=for-the-badge\&logo=python\&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13+-4C72B0?style=for-the-badge\&logo=python\&logoColor=white)

</p>

<p align="center">

![Level](https://img.shields.io/badge/Level-Beginner%20→%20Intermediate-00C853?style=flat-square)
![Status](https://img.shields.io/badge/Status-Currently%20Learning-FF9800?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-Data%20Analysis-6C63FF?style=flat-square)

</p>

---

## 👋 About

This repository documents my journey of learning **Python for Data Analysis**.

The focus is on building practical skills by working with arrays, datasets, statistics, visualization, and data-cleaning techniques.

```text
Python
   │
   ├── NumPy
   │
   ├── Pandas
   │
   ├── Matplotlib / Seaborn
   │
   └── Data Analysis
           │
           ▼
      Machine Learning
```

---

# 📊 Skills & Progress

<p align="center">

| Skill               |           Progress          |
| :------------------ | :-------------------------: |
| 🐍 Python           | `████████████████████` 100% |
| 🔢 NumPy            |  `██████████████████░░` 90% |
| 🐼 Pandas           |  `███████████████░░░░░` 75% |
| 🧹 Data Cleaning    |  `█████████████░░░░░░░` 65% |
| 📊 Matplotlib       |  `████████████░░░░░░░░` 60% |
| 🎨 Seaborn          |  `███████░░░░░░░░░░░░░` 35% |
| 🔍 Data Analysis    |  `█████████░░░░░░░░░░░` 45% |
| 🤖 Machine Learning |  `████░░░░░░░░░░░░░░░░` 20% |

</p>

> Progress represents my current learning stage, not a formal skill assessment.

---

# 🧭 Learning Roadmap

```text
                 ┌───────────────┐
                 │    Python     │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │     NumPy     │
                 └───────┬───────┘
                         │
                         ▼
                 ┌───────────────┐
                 │    Pandas     │
                 └───────┬───────┘
                         │
                         ▼
              ┌──────────────────────┐
              │    Data Cleaning     │
              └──────────┬───────────┘
                         │
                         ▼
             ┌────────────────────────┐
             │ Matplotlib / Seaborn   │
             └────────────┬───────────┘
                          │
                          ▼
                ┌─────────────────┐
                │ Data Analysis   │
                └────────┬────────┘
                         │
                         ▼
                ┌─────────────────┐
                │ Machine Learning│
                └─────────────────┘
```

### ✅ Completed

* [x] NumPy fundamentals
* [x] Array creation
* [x] Array properties
* [x] Indexing & slicing
* [x] Boolean masking
* [x] Fancy indexing
* [x] Reshaping
* [x] Pandas DataFrames
* [x] Pandas Series
* [x] Filtering & sorting
* [x] GroupBy & aggregation
* [x] CSV loading
* [x] Basic data inspection
* [x] Missing-value detection
* [x] Duplicate detection
* [x] Basic data cleaning
* [x] Histogram
* [x] Line plots
* [x] Trigonometric visualization

### 🔜 Next

* [ ] `loc` and `iloc`
* [ ] Advanced Pandas
* [ ] Missing-value handling
* [ ] Data type conversion
* [ ] Merge & Join
* [ ] Pivot Tables
* [ ] Advanced Seaborn
* [ ] Exploratory Data Analysis
* [ ] Statistical Analysis
* [ ] Machine Learning

---

# 📚 Topics

<details>
<summary><b>🔢 NumPy — Array Fundamentals</b></summary>

### Array Creation

```python
import numpy as np

a = np.array([1, 2, 3, 4, 5])
b = np.zeros((3, 3))
c = np.ones((2, 4))
d = np.arange(0, 10, 2)
e = np.linspace(0, 1, 5)
```

### Array Properties

```python
print(a.shape)
print(a.dtype)
print(a.ndim)
print(a.size)
```

### Reshaping

```python
matrix = np.arange(12).reshape(3, 4)

print(matrix)
```

</details>

---

<details>
<summary><b>🎯 NumPy — Indexing & Slicing</b></summary>

```python
arr = np.array([10, 20, 30, 40, 50])

print(arr[0])       # 10
print(arr[-1])      # 50
print(arr[1:4])     # [20 30 40]
```

### 2D Indexing

```python
matrix = np.array([
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
])

print(matrix[1, 2])
print(matrix[:, 1])
print(matrix[0:2, :])
```

</details>

---

<details>
<summary><b>🔍 NumPy — Boolean & Fancy Indexing</b></summary>

### Boolean Masking

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

```python
arr = np.array([10, 20, 30, 40, 50])

indexes = [0, 3, 4]

print(arr[indexes])
```

</details>

---

<details>
<summary><b>📊 Matplotlib — Histogram</b></summary>

A histogram helps visualize the distribution of numerical data.

```python
import numpy as np
import matplotlib.pyplot as plt

data = np.random.normal(70, 10, 1000)

plt.hist(
    data,
    bins=17,
    edgecolor="gray",
    alpha=0.7
)

plt.axvline(
    data.mean(),
    color="gray",
    linestyle="--",
    label="Mean"
)

plt.title("Exam Score Distribution")
plt.xlabel("Score")
plt.ylabel("Frequency")
plt.legend()

plt.show()
```

</details>

---

<details>
<summary><b>📐 Matplotlib — Trigonometric Functions</b></summary>

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0, 10, 100)

plt.plot(x, np.sin(x), label="sin(x)")
plt.plot(x, np.cos(x), label="cos(x)")

plt.title("Trigonometric Functions")
plt.xlabel("x")
plt.ylabel("y")

plt.grid(True)
plt.legend()
plt.show()
```

This demonstrates how mathematical functions can be visualized using Python.

</details>

---

<details>
<summary><b>🐼 Pandas — DataFrame & Series</b></summary>

### DataFrame

```python
import pandas as pd

df = pd.DataFrame({
    "Name": ["Alice", "Bob", "Charlie"],
    "Age": [25, 30, 35],
    "Score": [88.5, 92.3, 79.1]
})

print(df)
```

### Series

```python
ages = df["Age"]

print(type(ages))
```

### Inspection

```python
print(df.shape)
print(df.dtypes)
print(df.describe())
```

</details>

---

<details>
<summary><b>🔎 Pandas — Filtering & Sorting</b></summary>

```python
df = pd.DataFrame({
    "Name": ["Alice", "Bob", "Charlie", "Diana"],
    "Dept": ["IT", "HR", "IT", "HR"],
    "Salary": [70000, 65000, 80000, 72000]
})
```

### Filtering

```python
it_team = df[df["Dept"] == "IT"]

high_pay = df[df["Salary"] > 70000]
```

### Sorting

```python
sorted_df = df.sort_values(
    "Salary",
    ascending=False
)
```

### New Column

```python
df["Bonus"] = df["Salary"] * 0.10
```

</details>

---

<details>
<summary><b>📈 Pandas — GroupBy & Aggregation</b></summary>

```python
dept_avg = (
    df.groupby("Dept")["Salary"]
      .mean()
)

print(dept_avg)
```

`groupby()` allows data to be divided into groups and analyzed independently.

</details>

---

<details>
<summary><b>📂 Pandas — Loading CSV Data</b></summary>

```python
import pandas as pd

df = pd.read_csv(
    "retail_store_sales.csv"
)

print(df)
```

### Initial Inspection

```python
df.info()

print(df.describe())
```

</details>

---

<details>
<summary><b>🧹 Data Cleaning</b></summary>

### Missing Values

```python
missing = df.isnull().mean() * 100

print(missing)
```

### Duplicate Rows

```python
duplicates = df[df.duplicated()]

print(duplicates)
```

### Create a Working Copy

```python
df_clean = df.copy()
```

### Remove Unnecessary Column

```python
df_clean = df_clean.drop(
    columns=["Transaction ID"]
)
```

</details>

---

# 📈 Project Highlights

## 🛒 Retail Store Sales Analysis

**Dataset:** `retail_store_sales.csv`

The project focuses on understanding and preparing a real-world style retail dataset.

### Workflow

```text
CSV Dataset
     │
     ▼
Load Data
     │
     ▼
Inspect Dataset
     │
     ├── Shape
     ├── Data Types
     └── Statistics
     │
     ▼
Check Missing Values
     │
     ▼
Check Duplicates
     │
     ▼
Clean Data
     │
     ▼
Ready for Analysis
```

### Concepts Practiced

* Dataset loading
* Data inspection
* Statistical summary
* Missing-value analysis
* Duplicate detection
* Column removal
* Data preparation

---

# 🧹 Data Analysis Workflow

My general approach to a dataset:

```text
        📂 DATA
          │
          ▼
    ┌───────────────┐
    │ Load Dataset  │
    └───────┬───────┘
            ▼
    ┌───────────────┐
    │ Inspect Data  │
    └───────┬───────┘
            ▼
    ┌───────────────┐
    │ Clean Data    │
    └───────┬───────┘
            ▼
    ┌───────────────┐
    │ Explore Data  │
    └───────┬───────┘
            ▼
    ┌───────────────┐
    │ Visualize     │
    └───────┬───────┘
            ▼
    ┌───────────────┐
    │ Find Insights │
    └───────┬───────┘
            ▼
         💡 RESULT
```

---

# 🧠 Key Learnings

This repository helped me understand how to move from **raw Python code to practical data analysis**.

### NumPy

`Arrays → Indexing → Slicing → Masking → Reshaping`

### Pandas

`DataFrame → Filtering → Sorting → GroupBy → Analysis`

### Visualization

`Data → Plot → Understand → Communicate`

### Data Cleaning

`Raw Data → Inspect → Clean → Prepare`

---

# 📁 Project Structure

```text
python-data-analysis/
│
├── 📄 README.md
├── 🐍 data_analysis.py
├── 📊 retail_store_sales.csv
└── 📦 requirements.txt
```

### `data_analysis.py`

Contains NumPy, Pandas, Matplotlib and Seaborn practice programs.

### `retail_store_sales.csv`

Dataset used for data cleaning and analysis.

### `requirements.txt`

```text
numpy
pandas
matplotlib
seaborn
```

---

# 🚀 Future Plans

* 📊 Build complete EDA projects
* 🧹 Practice advanced data cleaning
* 📈 Create better visualizations
* 🐼 Learn advanced Pandas
* 🎨 Explore Seaborn deeply
* 📂 Work with larger datasets
* 📊 Build data-analysis dashboards
* 🤖 Start Machine Learning
* 🚀 Build end-to-end projects

---

# 🏁 Learning Journey

```text
🐍 Python
   │
   ▼
🔢 NumPy
   │
   ▼
🐼 Pandas
   │
   ▼
🧹 Data Cleaning
   │
   ▼
📊 Visualization
   │
   ▼
🔍 Exploratory Data Analysis
   │
   ▼
🤖 Machine Learning
   │
   ▼
🧠 Data Science
```

---

# ⭐ Repository Goal

> **Learn the fundamentals → practice with code → work with real data → analyze → visualize → build projects.**

---

<p align="center">

### 💻 Learn • Practice • Analyze • Build

</p>

<p align="center">

**🐍 Python → 🔢 NumPy → 🐼 Pandas → 📊 Visualization → 🔍 Data Analysis → 🤖 ML**

</p>

<p align="center">
  ⭐ If you're also learning Python Data Analysis, feel free to explore this repository.
</p>
