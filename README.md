# Python-Pandas-Projects-
A collection of Python projects exploring data analysis with Pandas. Includes hands‑on exercises for loading, cleaning, grouping, and visualising datasets using Pandas, Matplotlib, and Seaborn. 
# Python Fundamentals & Data Analysis Project (Pandas)

A collection of Python exercises and mini-projects completed as part of my **Data Technician Bootcamp**, covering core Python programming fundamentals through to real data analysis and visualisation using Pandas, all developed in **Google Colab**.

## 🛠️ Tools & Libraries Used
- 🐍 Python
- 📘 Pandas
- 🔢 NumPy
- 📊 Matplotlib
- 🎨 Seaborn
- 📝 Jupyter Notebook / Google Colab
- ☁️ Google Drive (for mounting and file storage)

## 🧰 Skills Demonstrated

### Core Python Fundamentals
- **Variables** – storing and referencing data such as names, ages, marks, and prices
- **print() and input()** – displaying output and collecting user input
- **Type casting** – converting user input to `int` or `float` to perform calculations (input is stored as text by default)
- **Data types** – checking variable types using `type()`
- **Arithmetic operators** – addition, subtraction, multiplication, division (`/`), floor division (`//`), modulus (`%`), and exponents (`**`)
- **Shortcut/compound assignment operators** – `+=`, `-=`, `*=`, `/=`, `//=`, `%=` to update a variable's value in place
- **Comparison operators** – `==`, `!=`, `>`, `<`, `>=`, `<=` to compare values and return Boolean results
- **if / elif / else statements** – conditional logic to control program flow
- **for loops and while loops** – repeating logic and iterating over ranges of values
- **Debugging** – identifying and fixing syntax errors (mismatched quotes, missing brackets, typos in function names)

### Setting Up a Data Analysis Environment (Google Colab)
- Installing libraries not built into Colab using `!pip install`
- Importing core libraries: `pandas`, `numpy`, `matplotlib.pyplot`, `seaborn`
- Setting global display options (e.g. `pd.set_option`, `sns.set(style="whitegrid")`)
- Mounting **Google Drive** to access and store files directly from a Colab notebook
- Uploading dataset files (`files.upload()`) and saving copies back to Google Drive with `shutil.copy()`
- Understanding Colab session/runtime behaviour (e.g. re-mounting Drive after a runtime restart)

### Working with DataFrames (Pandas)
- Understanding what a DataFrame is – a table-like structure of rows and columns, where each column can hold a different data type
- Creating DataFrames from dictionaries, lists of lists, or by reading directly from a CSV file with `pd.read_csv()`
- Exploring a dataset with `.head()`, `.tail()`, `.info()`, `.describe()`, `.shape`, `.columns`, and `.dtypes`
- Displaying all rows/columns without truncation using `pd.set_option()`
- Finding unique values with `.unique()` and counting value frequency with `.value_counts()`
- Sorting data with `.sort_values()` (ascending and descending)
- Taking user input to dynamically control output (e.g. asking how many rows to display)

### 📈 Basic Visualisation
I used Matplotlib and Seaborn to create:
- Bar charts
- Histograms
- Box plots
- Scatter plots

## 📓 Notebook
The full code, outputs, and charts for this project are available here: [practice.ipynb](./practice.ipynb)

Developed and tested in **Google Colab**, which allowed me to write and run Python code, install libraries, mount Google Drive, upload datasets, and visualise results directly in the browser without any local setup.

## 🎯 Purpose
This project strengthened my understanding of core Python programming logic — variables, operators, conditionals, and loops — and showed how those fundamentals extend naturally into real data analysis workflows using Pandas, from setting up an environment and loading data through to exploring, sorting, and visualising it. These are essential foundational skills for a **Data Technician** role.

---
*Part of my ongoing journey transitioning into a career in data and technology.*
