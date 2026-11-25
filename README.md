📊 Pandas Analyzer & Data Visualization

A menu-driven Python project for analyzing sales data using **Pandas**,
**NumPy**, **Matplotlib**, and **Seaborn**. The application loads sales
data from a CSV file, explores and cleans the dataset, performs data
manipulation and statistical analysis, and creates visualizations to
help identify sales trends and patterns.

🎯 Project Objective

The objective of this project is to build a comprehensive sales data
analysis and visualization tool in Python. It provides hands-on practice
with real-world data operations, DataFrame manipulation, statistical
functions, and data visualization.

✨ Features

📁 1. Dataset Management

-   Load sales data from a CSV file.
-   Store the dataset in a Pandas DataFrame.
-   Handle file-loading errors and invalid paths.

🔍 2. Data Exploration

-   Display the first and last five rows.
-   Display column names and data types.
-   Show dataset information using `info()`.
-   Generate an overview using `describe()`.

🧹 3. Data Cleaning

-   Identify rows containing missing values.
-   Fill missing values using the mean.
-   Drop rows containing missing values.
-   Replace missing values with a user-provided value.
-   Perform data type conversions when required.

🧮 4. DataFrame and NumPy Operations

-   Convert relevant DataFrame columns into NumPy arrays.
-   Demonstrate array indexing and slicing.
-   Perform element-wise mathematical operations.
-   Combine DataFrames using concatenation, merging, or joining.
-   Split data based on regions, products, or other criteria.
-   Search, sort, and filter sales records.

📈 5. Aggregation and Statistical Analysis

-   Apply aggregation functions such as `sum()`, `mean()`, and
    `count()`.
-   Calculate standard deviation, variance, and percentiles.
-   Use Pandas functions such as `describe()`, `std()`, `var()`, and
    `quantile()`.
-   Create pivot tables to summarize sales data.
-   Use `groupby()` and `transform()` for grouped analysis.

🎨 6. Data Visualization

**Matplotlib** - Bar charts - Line charts - Scatter plots - Pie charts -
Histograms - Stack plots - Subplots, titles, labels, and legends - Save
charts as image files such as PNG or JPEG

**Seaborn** - Heatmaps - Box plots - Additional statistical
visualizations - Customized plot styling

🏗️ 7. Object-Oriented Design

The project organizes its functionality inside the `SalesDataAnalyzer`
class. Its documented structure includes:

-   `self.data` --- stores the sales data as a Pandas DataFrame.
-   `__init__()` --- initializes the analyzer and loads data.
-   `__del__()` --- performs cleanup if required.
-   `load_data(file_path)` --- loads a CSV file.
-   `explore_data()` --- displays basic dataset information.
-   `clean_data()` --- handles missing values and data cleaning.
-   `mathematical_operations()` --- performs mathematical operations.
-   `combine_data(other_dataframe)` --- combines DataFrames.
-   `split_data()` --- splits data based on criteria.
-   `search_sort_filter()` --- searches, sorts, and filters records.
-   `aggregate_functions()` --- applies aggregation functions.
-   `statistical_analysis()` --- performs statistical calculations.
-   `create_pivot_table()` --- generates pivot tables.
-   `visualize_data()` --- creates visualizations using Matplotlib and
    Seaborn.

Additional helper methods can be added as needed. Inheritance, method
overriding, `super()`, and operator overloading are optional extensions.

🛠️ Technologies Used

-   **Python** --- application programming language
-   **Pandas** --- data loading, cleaning, and analysis
-   **NumPy** --- numerical and array operations
-   **Matplotlib** --- data visualization
-   **Seaborn** --- statistical data visualization
-   **Jupyter Notebook** --- development and documentation environment

🗂️ Project Structure

``` text
Pandas-Analyzer-and-Data-Visualization/
│
├── data/
│   └── sales_data.csv
│
├── visualizations/
│   └── (saved charts)
│
├── sales_analyzer.py
├── README.md
└── requirements.txt
```

> The filenames and folders above are a suggested organization. Update
> them to match the files in your GitHub repository.

⚙️ Installation

📥 1. Clone the repository

``` bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```

📦 2. Install the required libraries

``` bash
pip install pandas numpy matplotlib seaborn jupyter
```

Or install from the requirements file:

``` bash
pip install -r requirements.txt
```

📓 3. Start Jupyter Notebook (if your project uses a notebook)

``` bash
jupyter notebook
```

Open the project notebook and run its cells.

▶️ 4. Run the Python program (if using a Python script)

``` bash
python sales_analyzer.py
```

Make sure the CSV file path supplied to the program is correct.

🗃️ Dataset

The program expects sales data in **CSV format**. You can use a publicly
available sales dataset, such as a sales dataset from Kaggle, or prepare
a sample CSV file.

Example columns may include:

  Column      Description
  ----------- --------------------------------
  `SalesID`   Unique sales record identifier
  `Date`      Date of the transaction
  `Product`   Product name
  `Region`    Sales region
  `Sales`     Sales amount
  `Profit`    Profit amount
  `Year`      Year of the transaction

The exact columns depend on the dataset being used. Ensure that the
column names in the program match the CSV file.

🖥️ Application Menu

The sample console interface provides the following main options:

``` text
========== Data Analysis & Visualization Program ==========

Please select an option:
1. Load Dataset
2. Explore Data
3. Perform DataFrame Operations
4. Handle Missing Data
5. Generate Descriptive Statistics
6. Data Visualization
7. Save Visualization
8. Exit

===========================================================
```

🔄 Example Workflow

1.  Select **Load Dataset** and enter the CSV file path.
2.  Select **Explore Data** to inspect rows, columns, data types, and
    dataset information.
3.  Use **Perform DataFrame Operations** for data manipulation.
4.  Select **Handle Missing Data** to inspect and clean missing values.
5.  Generate descriptive statistics to understand the dataset.
6.  Select **Data Visualization** and choose a chart type.
7.  Save the generated visualization using **Save Visualization**.
8.  Select **Exit** to close the program.

📋 Example Dataset

A small sample of sales data could look like this:

    SalesID Product     Region         Sales   Year
  --------- ----------- ------------ ------- ------
        101 Product A   North            500   2022
        102 Product B   East             600   2022
        103 Product C   West Coast       700   2022
        104 Product D   South            800   2022
        105 Product E   North            550   2022

This is illustrative sample data; use the actual CSV dataset for
analysis.

🎓 Learning Outcomes

By completing this project, users can gain practical experience with:

-   Reading and analyzing CSV datasets using Pandas.
-   Cleaning missing data and preparing data for analysis.
-   Working with DataFrames and NumPy arrays.
-   Applying mathematical, aggregation, and statistical functions.
-   Combining, splitting, searching, sorting, and filtering data.
-   Creating pivot tables and grouped summaries.
-   Building and saving visualizations with Matplotlib and Seaborn.
-   Applying object-oriented programming concepts in Python.

🚀 Future Enhancements

-   Add more interactive filtering options.
-   Support exporting cleaned data and analysis results.
-   Add more chart types and visualization customization.
-   Improve input validation and error handling.
-   Add a graphical user interface.

👨‍💻 Author

**Harsh Prajapati**

📄 License

This project is intended for educational and learning purposes. Add a
license file to the repository if you want to specify permissions for
reuse and distribution.
