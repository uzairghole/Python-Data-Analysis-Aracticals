# 📊 Python Data Analysis & Visualization

A collection of Python projects focused on **NumPy, Pandas, Data Cleaning, Exploratory Data Analysis (EDA), and Data Visualization**.

## 🚀 Projects Included

### 1. Histogram Visualization
- Generate 1,000 exam scores using NumPy
- Visualize distribution with Matplotlib histogram

### 2. Trigonometric Plotting
- Plot `sin(x)` and `cos(x)` functions
- Add titles, labels, legends, and grids

### 3. NumPy Fundamentals
- Array creation
- Reshaping
- Dimensions and data types

### 4. Slicing & Boolean Masking
- Indexing and slicing
- Fancy indexing
- Boolean filtering

### 5. Pandas DataFrame Essentials
- DataFrame creation
- Data inspection
- Statistical summaries

### 6. Data Wrangling & Aggregation
- Filtering and sorting
- GroupBy operations
- Aggregations and calculated columns

### 7. Retail Sales EDA & Data Cleaning
Using a retail sales dataset:

- Load CSV files with Pandas
- Inspect dataset structure
- Generate descriptive statistics
- Check missing values
- Detect duplicate records
- Remove unnecessary columns
- Prepare data for analysis

#### Sample Operations

```python
df = pd.read_csv("retail_store_sales.csv")

# Dataset overview
df.info()
df.describe()

# Missing values
df.isnull().mean() * 100

# Remove unwanted column
df.drop(columns=["Transaction ID"])
