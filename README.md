# Task_2_DA
# Supermarket Sales EDA

This repository contains a comprehensive Exploratory Data Analysis (EDA) of the Supermarket Sales dataset. The main objective of this project is to analyze supermarket sales data to uncover insights about customer behavior, product performance, payment methods, and overall sales trends. This analysis can help inform strategic business decisions, optimize inventory management, and improve marketing and sales strategies.

## What I Did

- **Data Loading and Initial Inspection:**
  - Loaded the dataset using Pandas and explored the first few rows to understand the structure.
  - Checked column data types and verified the absence of missing values.
  - Used `.info()`, `.describe()`, and `.head()` to summarize the dataset, providing a clear overview of numerical and categorical features.

- **Univariate Analysis:**
  - For numerical features such as `Unit price`, `Quantity`, `Tax 5%`, `Sales`, `cogs`, `gross margin percentage`, `gross income`, and `Rating`, plotted histograms to observe the distribution, detect skewness, and identify patterns.
  - Used boxplots to detect outliers and understand the spread and variability in the data.
  - For categorical features like `Branch`, `City`, `Customer type`, `Gender`, `Product line`, and `Payment`, created countplots to observe category frequencies and understand dominant categories.

- **Bivariate Analysis:**
  - Analyzed relationships between numerical variables using correlation heatmaps to identify strong positive or negative correlations.
  - Investigated how sales and other metrics vary across different product lines, branches, and customer segments using grouped aggregations and visualizations.
  - Explored the influence of customer type and gender on purchasing behavior.

- **Segment Analysis:**
  - Grouped data by `Customer type` and `Gender` to determine which segments contribute the most to total sales.
  - Examined sales by product line to identify top-performing products.
  - Analyzed sales across branches and cities to highlight regional performance trends.

- **Time-Based Analysis:**
  - Converted the `Date` column to a datetime format and analyzed daily sales trends.
  - Detected patterns, seasonality, and peak sales periods over time.
  - Identified days with unusually high or low sales to understand consumer behavior.

- **Outlier Detection and Skewness Handling:**
  - Used boxplots and histograms to detect extreme values in `Quantity`, `Sales`, and other numerical features.
  - Checked the skewness of numerical variables and considered transformations for further analysis or predictive modeling.

- **Business Insights:**
  - Compiled actionable insights from the analysis, such as top-selling product lines, high-value customer segments, and preferred payment methods.
  - Identified trends that could guide inventory management, marketing strategies, and sales promotions.
  - Highlighted patterns and anomalies that could help improve operational efficiency.

## Tools Used
- Python 3.x
- Pandas for data manipulation
- Matplotlib and Seaborn for data visualization


