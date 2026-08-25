# Python-Pandas-Projects-
A collection of Python projects exploring data analysis with Pandas. Includes hands‑on exercises for loading, cleaning, grouping, and visualising datasets using Pandas, Matplotlib, and Seaborn. 
# Project Overview & GitHub README Summary

This repository contains the foundational Python and Data Analysis work completed as part of the **Data Technician Bootcamp**. The project demonstrates fundamental Python programming, data manipulation, file system integration in Google Colab, and introductory exploratory data analysis (EDA) using `pandas`.

---

## 🔑 Key Skills & Concepts Highlighted

* **Data Wrangling & Analysis:** Creating and manipulating DataFrames, checking structures (`df.info()`, `df.describe()`, `df.shape`), and cleaning column entries.


* **Environment Setup & Drive Integration:** Mount Google Drive within Google Colab runtimes and manage file paths (`shutil.copy`, `files.upload()`).


* **Python Foundations:** Dynamic variable declaration, data typing (`int`, `float`, `str`), and console inputs (`input()`).


* **Calculations & Logic:** Applying shortcut, arithmetic, and comparison operators to process dynamic data.


* **Debugging & Code Quality:** Identifying and fixing syntax/runtime errors (string quoting, mismatched brackets, function call typos).



---

## 📚 Libraries & Modules Used

```python
# Core Data Handling & Numerical Computing
import pandas as pd           # DataFrame manipulation, CSV import/export[cite: 2]
import numpy as np            # Numerical calculations and arrays[cite: 2]

# Data Visualization
import matplotlib.pyplot as plt # Base plotting and figure management[cite: 2]
import seaborn as sns         # Statistical graphics and styled visualization[cite: 2]

# System & Colab Utilities
from google.colab import drive # Mount Google Drive to Colab VM[cite: 2]
from google.colab import files # File uploader interface[cite: 2]
import shutil                 # File system operations and file transfer[cite: 5]

```

---

## 📊 Variables & Data Dictionary

Below is a reference guide to all variables initialized and tracked across the analysis workbooks:

### Notebook Setup & File System Variables

| Variable Name | Type / Source | Description |
| --- | --- | --- |
| `uploaded` | `dict` | Dictionary containing uploaded files via `files.upload()`.

 |
| `full_path` | `str` | File path string pointing to the uploaded student dataset (`'/content/student.csv'`).

 |
| `df` | `pandas.DataFrame` | Primary dataset loaded from `student.csv`.

 |
| `sorted_df` | `pandas.DataFrame` | DataFrame sorted alphabetically by student name.

 |
| `num_rows` | `int` | Dynamic user input specifying the number of rows to display via `df.head()`.

 |
| `total_columns` | `int` | Integer count of total columns present in `df`.

 |

### Python Foundations & Math Variables

| Variable Name | Type | Description |
| --- | --- | --- |
| `student_name` | `str` | Stores student name string.

 |
| `name`, `name1`, `name2` | `str` | String identifiers used for general string manipulations and prints.

 |
| `age` | `int` | Age stored as an integer.

 |
| `price`, `budget` | `float` / `int` | Numeric store for monetary values.

 |
| `colour` | `str` | User input store for interactive text queries.

 |
| `mark`, `mark1`, `mark2` | `int` / `float` | Grade marks used for scalar and DataFrame calculations.

 |
| `total`, `average` | `float` | Aggregated calculated values for grades and totals.

 |
| `max_mark`, `marks_below` | `int` | Boundary values used for comparative subtraction math.

 |
| `double_mark` | `int` | Scaled calculation values (`mark * 2`).

 |
| `num`, `num1`, `num2` | `int` / `float` | Generic arithmetic stores for operators and user inputs.

 |
| `points`, `score`, `count` | `int` / `float` | Counters tracking shortcut updates (`+=`, `-=`, `*=`, `/=`).

 |
| `length`, `speed`, `boxes` | `int` / `float` | Arithmetic variable tracking for division and integer division.

 |
| `cookies`, `rem`, `value` | `int` | Integer counters for floor division (`//`) and remainder (`%`) logic.

 |
| `a`, `b`, `x`, `y`, `n` | `int` / `float` | Comparative variables evaluated using logical operators (`==`, `!=`, `<`, `>`, `<=`, `>=`).

 |

---

## 📈 Charts & Visualization Setup

While core data structures were prepared using Pandas, visual output generation is enabled using `matplotlib` and `seaborn`:

* **Default Style:** `sns.set(style="whitegrid")` configured globally for visual styling.


* **Display Controls:** `pd.set_option("display.max_rows", None)` configured to inspect full evaluation tables without truncation.
