# FRAMEWORK FOR DATA AND VISUAL ANALYTICS 

## Fundamentals of Data Visualization and Analytics (FDVA)

This repository contains the laboratory experiments for **Fundamentals of Data Visualization and Analytics (FDVA)**. The experiments introduce Python-based data analysis, Exploratory Data Analysis (EDA), data cleaning, statistical analysis, data visualization, and visualization using **Power BI** and **Tableau**.

## Experiments Included

### Experiment 1 – Setting Up Python Environment and Libraries

* Create and use a Python/Jupyter Notebook.
* Write and execute Python programs.
* Create and use Code and Markdown cells.
* Demonstrate interactive widgets using `ipywidgets`.
* Implement an interactive slider and display its value.

### Experiment 2 – EDA: Data Import and Export

* Import data from CSV files.
* Import data from Excel files.
* Import tabular data from web pages using `pandas.read_html()`.
* Export a Pandas DataFrame to an Excel file.
* Work with different data formats.

### Experiment 3 – EDA: Data Cleaning

* Detect and handle missing values.
* Fill missing values using appropriate techniques.
* Remove duplicate records.
* Convert data types.
* Maintain consistency in categorical data.
* Perform Min-Max normalization.
* Perform standardization using `StandardScaler`.

### Experiment 4 – EDA: Data Inspection and Analysis

* Inspect DataFrames using `head()`, `tail()`, and `info()`.
* Generate descriptive statistics using `describe()`.
* Inspect dataset columns and unique values.
* Filter and analyze categorical data.
* Calculate:

  * Mean
  * Median
  * Mode
  * Range
  * Variance
  * Standard deviation

### Experiment 5 – EDA: Data Visualization

Learn to represent and understand data through graphical visualizations.

Visualizations covered:

* Line Chart
* Bar Chart
* Histogram

The experiment demonstrates how visualizations can be used to identify patterns, distributions, relationships, and possible anomalies in data.

### Experiment 6 – Data Visualization Using Power BI

* Explore the Power BI Desktop interface.
* Import data from Excel and CSV files.
* Clean and transform data using Power Query.
* Create calculated columns and measures.
* Create basic visualizations:

  * Bar Chart
  * Line Chart
  * Pie/Donut Chart
  * KPI Cards
  * Table/Matrix
* Add slicers and filters.
* Build an interactive dashboard.
* Save the Power BI report as a `.pbix` file.

### Experiment 7 – Data Visualization Using Tableau

* Explore the Tableau interface.
* Connect Tableau to Excel and CSV data.
* Create worksheets and dashboards.
* Build basic visualizations.
* Use filters and interactive features.
* Create an interactive dashboard and story.

## Technologies and Tools

* **Python**
* **Jupyter Notebook**
* **Google Colab**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **IPyWidgets**
* **Microsoft Power BI**
* **Tableau**

## Python Libraries

Install the required Python libraries using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn openpyxl ipywidgets
```

For Jupyter Notebook, widgets can be enabled/used through the `ipywidgets` package.

## Repository Structure

```text
FDVA-Lab/
│
├── README.md
│
├── Experiment-1/
│   └── Python_Environment_and_Widgets.ipynb
│
├── Experiment-2/
│   └── Data_Import_and_Export.ipynb
│
├── Experiment-3/
│   └── Data_Cleaning.ipynb
│
├── Experiment-4/
│   └── Data_Inspection_and_Analysis.ipynb
│
├── Experiment-5/
│   └── Data_Visualization.ipynb
│
├── Experiment-6/
│   └── PowerBI/
│       └── FDVA_Dashboard.pbix
│
├── Experiment-7/
│   └── Tableau/
│       └── FDVA_Dashboard
│
└── Datasets/
    ├── CSV files
    └── Excel files
```

## Learning Outcomes

After completing these experiments, students will be able to:

1. Set up and use a Python data analysis environment.
2. Import and export data from different sources.
3. Clean and preprocess datasets.
4. Inspect datasets and calculate descriptive statistics.
5. Create different types of data visualizations.
6. Build interactive dashboards using Power BI.
7. Create interactive visualizations and dashboards using Tableau.
8. Apply data analysis and visualization techniques to real-world datasets.

## Result

All seven experiments demonstrate fundamental techniques used in **data analysis, exploratory data analysis, and data visualization**. The laboratory provides practical experience with Python, Pandas, visualization libraries, Power BI, and Tableau.
