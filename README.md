# Pandas Learning Journey 🐼
### A Student's Path Toward Becoming an ML Engineer

---

## About This Repository

This repository documents my complete journey of learning Pandas — one of the most essential libraries in the Python data ecosystem. I'm Thrishanth, a fresher from Bengaluru, India, actively building my skills toward becoming a Machine Learning Engineer.

This isn't a tutorial. It's an honest record of everything I learned, practiced, and applied — from loading a CSV file for the first time to preparing production-ready datasets for ML models.

---

## Why Pandas?

Before touching any ML model, I realized that data preparation is where most of the real work happens. Pandas is the tool that makes that possible — cleaning messy data, exploring patterns, engineering features, and shaping datasets into something a model can actually learn from.

No Pandas skills = weak ML foundation. That's why I took this seriously.

---

## What This Repository Contains

This repository covers the complete Pandas skillset required for Machine Learning — from the very basics of exploring a dataset to preparing it fully for a model.

**Pandas Basics**
- Creating and understanding DataFrames
- Exploring data — `head()`, `tail()`, `info()`, `describe()`, `shape`
- Understanding index and column structures
- Loading data from CSV and Parquet files

**Accessing and Selecting Data**
- Row and column selection using `loc` and `iloc`
- Slicing DataFrames
- Sorting data with `sort_values()`
- Iterating through rows with `iterrows()`
- Working with `sample()` for random access

**Filtering Data**
- Boolean filtering with conditions
- Multi-condition filtering using `&` and `isin()`
- String-based filtering with `str.contains()` and `str.startswith()`
- Regex-based filtering for pattern matching
- Clean querying using `df.query()`

**Handling Missing Values**
- Detecting missing values with `isnull()` and `isnull().sum()`
- Dropping missing rows and columns with `dropna()`
- Filling missing values with `fillna()` — mean, median, mode strategies
- Understanding when to drop vs when to fill
- Visualizing missing data patterns

**Feature Engineering**
- Creating new columns from existing ones
- Dropping irrelevant columns with `df.drop()`
- Transforming columns using `apply()` and `lambda` functions
- Binning continuous data into categories with `pd.cut()`
- Renaming columns for clarity

**Encoding Categorical Data**
- Understanding why encoding matters for ML
- One-hot encoding with `pd.get_dummies()`
- Label encoding using Scikit-learn's `LabelEncoder`
- Ordinal encoding for ordered categories
- Handling high-cardinality categorical columns

**GroupBy and Aggregation**
- Grouping data with `df.groupby()`
- Aggregating with `.mean()`, `.sum()`, `.count()`, `.min()`, `.max()`
- Grouping by multiple columns
- Using `.agg()` for custom aggregations

**Merging and Joining Datasets**
- Combining DataFrames with `pd.merge()`
- Inner, outer, left, and right joins
- Stacking DataFrames with `pd.concat()`
- Handling duplicate columns after merging

**Correlation and Feature Selection**
- Computing correlation matrix with `df.corr()`
- Visualizing correlation with heatmaps
- Identifying and dropping highly correlated features
- Understanding correlation vs causation

**End-to-End EDA on Real Dataset**
- Full exploratory data analysis pipeline on a real Kaggle dataset
- Asking and answering questions from raw data
- Cleaning, filtering, engineering, and summarizing in one workflow
- Drawing insights before building any model

---

## My Learning Approach

I didn't just follow tutorials passively. After every concept, I opened a real dataset and tried to use what I learned without looking at notes. That friction — getting stuck, figuring it out, moving forward — is what actually built the understanding.


---

## Bigger Goal

This is one step in a structured 6-month roadmap I'm following to become a job-ready ML Engineer by December 2026. Pandas is the foundation. From here I move into Core ML Algorithms, Deep Learning, NLP, and eventually MLOps and model deployment.

Every file in this repository is a small proof that I showed up and did the work.

---

## Tools Used

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge&logo=python&logoColor=white)

---

## Connect With Me

If you're on a similar journey or have feedback on my work — feel free to connect.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/thrishanth-hs21)

---

*Learning in public. Building every day. Bengaluru, India.*
