# GO2COD_DS_01


# E-Commerce Customer Data Analysis (Exploratory Data Analysis)

## Project Overview
This project involves performing an Exploratory Data Analysis (EDA) on an E-commerce customer dataset. The primary objective is to uncover insights into customer behavior and how it correlates with the amount they spend annually. The steps include data cleaning, visualization, and statistical analysis to extract trends, correlations, and actionable insights.

---

## Files Included
- **`Ecommerce Customers.csv`**: The dataset used for analysis.
- **`EDA_Script.py`**: Python script that includes the EDA process, including data cleaning, visualizations, and analysis.
- **`README.md`**: This file, providing a summary of the project, tools, and insights.

---

## Dataset Information
The dataset consists of the following columns:

- **Avg. Session Length**: The average time (in minutes) a customer spends during a session.
- **Time on App**: Time (in minutes) a customer spends on the company's mobile app.
- **Time on Website**: Time (in minutes) a customer spends on the company’s website.
- **Length of Membership**: How long (in years) the customer has been with the company.
- **Yearly Amount Spent**: Total amount (in USD) spent by the customer annually.

---

## Steps Performed

### 1. Data Loading
- The dataset is loaded into a DataFrame using `pandas`, and the structure of the data is reviewed.
- The dataset is inspected for any missing or invalid values.

### 2. Data Cleaning
- The data was cleaned by checking for missing values and ensuring consistency in data types.
- Any outliers were identified for further analysis, but no removal or imputation was necessary.

### 3. Data Visualization
- **Histograms**: Created for each numerical feature to understand its distribution:
  - Avg. Session Length
  - Time on App
  - Time on Website
  - Length of Membership
  - Yearly Amount Spent
- **Boxplots**: Used to detect outliers in the numerical features.
- **Scatter Plot**: Plotted `Time on App` against `Yearly Amount Spent` to understand their relationship.
- **Pairplot**: Visualized pairwise relationships between all numerical features.

### 4. Statistical Analysis
- Summary statistics such as mean, median, and standard deviation for all numerical columns.
- Observed relationships and trends between features were analyzed to provide business insights.

---

## Key Insights

- **Time on App** and **Length of Membership** are strong predictors of **Yearly Amount Spent**.
  - Customers who use the app more tend to spend more.
  - Longer customer retention leads to higher yearly spending.
  
- **Time on Website** has a weaker correlation with **Yearly Amount Spent**.
  - Improving app engagement may drive higher revenue compared to website engagement.

- **Outliers** represent high-value customers.
  - These customers could be targeted with loyalty programs or personalized offers to maximize lifetime value.

---

## Tools Used
- **Python**: The programming language used for the analysis.
- **Pandas**: For data loading and manipulation.
- **Seaborn & Matplotlib**: For data visualization.
- **Jupyter Notebook**: For interactive analysis and executing the code.

---

## Conclusion
The EDA provided valuable insights into customer behavior, indicating that focusing on app engagement and customer retention can drive higher spending. High-value customers (outliers) offer an opportunity for targeted marketing strategies.

---

## How to Use

1. Clone this repository and download the dataset (`Ecommerce Customers.csv`).
2. Run the provided Python script or load the notebook in Jupyter to reproduce the analysis.
3. The visualizations will help you better understand the distribution, outliers, and trends within the dataset.

Feel free to modify and explore additional insights, relationships, or use this template for your own analysis projects.`
