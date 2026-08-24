
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

🛠️ Technologies
Python
NumPy
Pandas
Matplotlib
📦 Installation
pip install numpy pandas matplotlib

📂 Project Structure
python-data-analysis-projects/
│
├── 01_histogram_visualization
├── 02_trigonometric_plotting
├── 03_numpy_fundamentals
├── 04_slicing_masking
├── 05_pandas_dataframe
├── 06_data_wrangling
└── 07_retail_sales_eda

🎯 Skills Learned
Data Cleaning
Data Wrangling
Exploratory Data Analysis (EDA)
Data Visualization
NumPy Fundamentals
Pandas Operations
CSV File Handling
👨‍💻 Author

Uzair Ghole

Python • Data Analysis • Pandas • NumPy • Data Visualization


**Ek aur important fix:** Aapke code me duplicate check galat likha hua hai.

```python
df[df.duplicated]


Iski jagah:

df[df.duplicated()]


ya

print(df.duplicated().sum())


