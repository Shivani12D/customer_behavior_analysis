# customer_behavior_analysis
Data Analytics Project  Showcasing Customer Behavior Analysis Using Python.SQL, and Power BI
# 📊 Data Analytics Project – Customer Behavior Analysis

## 1. Overview

This project focuses on analyzing customer data to identify patterns, understand customer behavior, and generate meaningful business insights.

The project follows an end-to-end data analytics workflow, starting with loading and exploring datasets in Python, cleaning and preparing data, performing SQL analysis using PostgreSQL, and creating an interactive Power BI dashboard to visualize key findings.

The main objective is to transform raw data into useful insights that can support better business decision-making.

## 2. Dataset

- **Format:** CSV
- **Description:** The dataset contains customer-related information used to analyze purchasing patterns and behavior.
- **Data Preparation:** Checked for missing values, duplicate records, incorrect data types, and inconsistencies.

## 3. Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data loading and analysis |
| Pandas | Data manipulation and cleaning |
| NumPy | Numerical operations |
| Matplotlib / Seaborn | Exploratory Data Analysis (EDA) |
| PostgreSQL | Database management and SQL queries |
| pgAdmin | Running and managing SQL queries |
| Power BI | Interactive dashboard creation |
| Jupyter Notebook | Python development environment |

## 4. Project Steps

### Step 1: Data Loading
- Imported the dataset into Python using Pandas.
- Checked dataset structure, rows, columns, and data types.
- Reviewed initial records to understand the data.

### Step 2: Exploratory Data Analysis (EDA)
- Analyzed numerical and categorical columns.
- Identified trends and patterns.
- Used visualizations to understand data distribution.
- Explored relationships between different variables.

### Step 3: Data Cleaning
- Checked and handled missing values.
- Identified and removed duplicate records where appropriate.
- Corrected data types and inconsistent values.
- Prepared the dataset for further analysis.

### Step 4: SQL Analysis Using PostgreSQL
- Imported the cleaned dataset into PostgreSQL.
- Performed SQL queries to extract meaningful insights.
- Used filtering, sorting, grouping, and aggregate functions.
- Analyzed customer behavior and purchasing patterns.

### Step 5: Power BI Dashboard
- Connected the analyzed data to Power BI.
- Created interactive charts, graphs, and KPIs.
- Designed a dashboard to present important findings.
- Used visualizations to make business insights easy to understand.

## 5. Dashboard

The Power BI dashboard provides a visual overview of the analysis.

**Key dashboard elements:**
- Customer and purchase-related KPIs.
- Customer behavior analysis.
- Purchasing frequency and trends.
- Category-wise analysis.
- Interactive charts and filters.

**Dashboard Preview:**
<img width="1352" height="726" alt="image" src="https://github.com/user-attachments/assets/ac6b604b-0082-4dba-be67-029361e1cf37" />


## 6. Key Results & Insights

- Identified important patterns in customer purchasing behavior.
- Analyzed customer trends using Python and SQL.
- Improved data quality through cleaning and preprocessing.
- Extracted meaningful business insights using PostgreSQL.
- Presented findings through an interactive Power BI dashboard.

## 7. How to Run the Project

Follow these steps to run the project locally:

**Prerequisites:**
- Python installed
- PostgreSQL and pgAdmin installed
- Power BI Desktop installed
- Jupyter Notebook installed

**Step 1: Clone the repository**

```bash
git clone https://github.com/your-username/your-repository.git
```

**Step 2: Navigate to the project folder**

```bash
cd your-repository
```

**Step 3: Install required Python libraries**

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary jupyter
```

**Step 4: Run the Jupyter Notebook**

```bash
jupyter notebook
```

**Step 5: Perform SQL Analysis**

- Create a database in PostgreSQL.
- Import the cleaned dataset.
- Execute the provided SQL queries using pgAdmin.

**Step 6: Open the Power BI Dashboard**

- Open the `.pbix` file in Power BI Desktop.
- Configure the database connection if required.
- Refresh the data to view the dashboard.

## 8. Project Structure

```text
Customer-Behavior-Analysis/
│
├── dataset/
│   └── customer_data.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── customer_dashboard.pbix
│
├── README.md
└── requirements.txt
```

## 9. Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Python for Data Analytics
- SQL Queries and PostgreSQL
- Data Visualization
- Power BI Dashboard Development
- Analytical Thinking and Problem-Solving

## 10. Conclusion

This project demonstrates an end-to-end data analytics workflow using Python, PostgreSQL, and Power BI. It helped develop practical skills in data preparation, database querying, data visualization, and extracting meaningful insights from raw datasets.
