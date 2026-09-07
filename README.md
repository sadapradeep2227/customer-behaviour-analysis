# customer-behaviour-analysis
# 📊 Data Analytics Project

## Overview

This project demonstrates an end-to-end **data analytics workflow**, from loading and cleaning raw data to extracting insights using Python and SQL, and presenting the results through an interactive **Power BI dashboard**.

The project covers:

* Data loading and exploration using Python
* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* SQL analysis using PostgreSQL / MySQL / SQL Server
* Interactive dashboard development in Power BI
* Business insights and analytical reporting
* Presentation creation using Gamma

---

## 📁 Dataset

The project uses a structured dataset containing business-related data for analysis.

The dataset was processed to:

* Understand the structure and quality of the data
* Identify missing and duplicate values
* Detect inconsistencies and outliers
* Prepare clean data for SQL and visualization
* Generate meaningful business insights

**Dataset:** `customer_shopping_behaviour.csv`

---

## 🛠️ Tools & Technologies

| Tool                                | Purpose                           |
| ----------------------------------- | --------------------------------- |
| **Python**                          | Data loading, cleaning & EDA      |
| **Pandas**                          | Data manipulation                 |
| **NumPy**                           | Numerical analysis                |
| **Matplotlib / Seaborn**            | Data visualization                |
| **PostgreSQL / MySQL / SQL Server** | SQL analysis                      |
| **Power BI**                        | Interactive dashboard             |
| **Gamma**                           | Presentation creation             |
| **Jupyter Notebook**                | Python analysis                   |
| **Git & GitHub**                    | Version control & project sharing |

---

## 🔄 Project Workflow

### 1. Data Loading

The dataset was loaded into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("customer_ahopping_behaviour.csv")

print(df.head())
print(df.shape)
```

### 2. Exploratory Data Analysis

EDA was performed to understand the dataset and identify important patterns.

Key activities included:

* Checking dataset dimensions
* Understanding data types
* Statistical analysis
* Identifying missing values
* Checking duplicate records
* Analyzing distributions
* Identifying trends and outliers

### 3. Data Cleaning

The raw dataset was cleaned and prepared for further analysis.

Steps included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Standardizing column names
* Handling inconsistent values
* Removing unnecessary columns
* Validating the final dataset

### 4. SQL Analysis

The cleaned data was imported into a relational database.

SQL queries were used to answer business questions and generate insights.

Examples of analysis:

```sql
SELECT category,
       COUNT(*) AS total_records
FROM sales
GROUP BY category
ORDER BY total_records DESC;
```

Other SQL techniques used include:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `JOIN`
* Aggregate functions
* Subqueries
* CTEs
* Window functions

### 5. Power BI Dashboard

The cleaned data and SQL results were used to build an interactive Power BI dashboard.

The dashboard focuses on key business KPIs, trends, comparisons, and performance metrics.

**Dashboard includes:**

* KPI cards
* Interactive charts
* Trend analysis
* Category/segment analysis
* Filters and slicers
* Business performance insights

---

## 📊 Dashboard

The Power BI dashboard provides an interactive view of the most important insights from the analysis.

### Dashboard Preview
<img width="1301" height="733" alt="Screenshot 2026-09-06 183348" src="https://github.com/user-attachments/assets/1b7ffd62-f6d8-439e-8e4b-93d4e26dab6d" />


---

## 📈 Results & Key Insights

The analysis helped identify important patterns and trends within the dataset.

Key findings include:

* Identified major performance trends
* Compared different categories and segments
* Analyzed changes over time
* Identified high- and low-performing areas
* Used SQL to answer business-focused questions
* Created visual KPIs for easier decision-making

> **Business Impact:** The project demonstrates how raw data can be transformed into actionable insights using Python, SQL, and Power BI.

---

## 📑 Project Deliverables

The project includes the following deliverables:

```text
├── Python EDA Notebook
├── Cleaned Dataset
├── SQL Queries
├── Power BI Dashboard
├── Analytical Report
└── Gamma Presentation
```

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/your-repository.git
cd your-repository
```

### 2. Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Run the Jupyter Notebook

```bash
jupyter notebook
```

Open the EDA notebook and run the cells to reproduce the analysis.

### 4. Run SQL Analysis

Import the cleaned dataset into your preferred database:

* PostgreSQL
* MySQL
* SQL Server

Then execute the SQL scripts available in:

```text
sql/
```

### 5. Open the Power BI Dashboard

Open the Power BI `.pbix` file located in:

```text
powerbi/
```

Update the data source if required and refresh the dashboard.

---

## 📂 Repository Structure

```text
data-analytics-project/
│
├── data/
│   ├── raw/
│   └── cleaned/
│
├── notebooks/
│   └── EDA.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── analytical_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

## 🎯 Skills Demonstrated

This project demonstrates practical skills in:

* Data Analysis
* Exploratory Data Analysis
* Data Cleaning
* Python & Pandas
* SQL
* PostgreSQL / MySQL / SQL Server
* Data Visualization
* Power BI
* Business Intelligence
* Reporting
* Data Storytelling
* Presentation Development

---

## 👨‍💻 Author

**S.Sadasivam**

Data Analyst | Python | SQL | Power BI

📧 Email: [sadapradeep654@gmail.com](mailto:sadapradeep654@gmail.com)
🔗 LinkedIn: [linkedin.com/in/sada-sivam-2227](linkedin.com/in/sada-sivam-2227)


---

⭐ If you found this project useful, feel free to star the repository!

