# 🚦 Accident Intelligence Platform

![Python](https://img.shields.io/badge/Python-3.11-blue)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1)
![SQL](https://img.shields.io/badge/Language-SQL-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-important)
![NumPy](https://img.shields.io/badge/Library-NumPy-orange)
![Plotly](https://img.shields.io/badge/Visualization-Plotly-3F4F75)
![Visualization](https://img.shields.io/badge/Visualization-Matplotlib%20%7C%20Seaborn-yellow)
![EDA](https://img.shields.io/badge/Analysis-Exploratory%20Data%20Analysis-success)
![Project](https://img.shields.io/badge/Project-Accident%20Intelligence-brightgreen)
![Jupyter](https://img.shields.io/badge/Environment-Jupyter%20Notebook-F37626)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

# 📌 Overview

Accident Intelligence Platform is a comprehensive data analytics project focused on analyzing road accident records stored in a MySQL database.

The project combines SQL-based data extraction with Python-powered analytics to transform raw accident records into meaningful insights. The dataset was translated into English, cleaned, standardized, and analyzed to identify accident trends, severity patterns, and risk factors.

The entire workflow follows an end-to-end analytics pipeline that demonstrates database querying, data preprocessing, exploratory data analysis (EDA), and interactive visualization techniques.

---

# 🧠 Business Problem

Road accidents generate large volumes of structured data that often remain underutilized.

Organizations and transportation authorities need reliable analytical approaches to understand:

* Accident frequency patterns
* Severity distributions
* Risk-prone conditions
* Time-based trends
* Location-based accident behavior
* Contributing environmental factors

This project aims to convert accident records into actionable intelligence that can support road safety initiatives and future predictive analytics systems.

---

# 🏗️ Project Workflow

```text
MySQL Database
      ↓
SQL Queries
      ↓
Pandas DataFrames
      ↓
Data Translation
      ↓
Data Cleaning
      ↓
Exploratory Data Analysis
      ↓
Visualization
      ↓
Insights & Recommendations
```

---

# 📂 Database Overview

The project utilizes accident-related records stored in MySQL.

| Table Category       | Description                           |
| -------------------- | ------------------------------------- |
| Accident Records     | Core accident details                 |
| Location Data        | Geographic information                |
| Road Conditions      | Surface and infrastructure conditions |
| Weather Information  | Environmental conditions              |
| Vehicle Details      | Vehicle-related attributes            |
| Casualty Information | Injury and fatality records           |

---

# 🔄 End-to-End Workflow

## 🔹 1. Database Connection

* Connected Python with MySQL
* Retrieved accident records using SQL queries
* Loaded data into Pandas DataFrames

```python
import pandas as pd
import mysql.connector

connection = mysql.connector.connect(
    host="localhost",
    user="root",
    password="password",
    database="accident_db"
)

query = "SELECT * FROM accidents"
df = pd.read_sql(query, connection)
```

---

## 🔹 2. Data Translation

Performed translation and standardization of non-English values:

* Category mapping
* Label standardization
* Text normalization

---

## 🔹 3. Data Cleaning

Preprocessing activities included:

* Missing value handling
* Duplicate removal
* Datatype correction
* Outlier inspection
* Data consistency validation

---

## 🔹 4. Exploratory Data Analysis (EDA)

Analysis focused on:

* Accident frequency
* Severity trends
* Temporal analysis
* Categorical distributions
* Relationship analysis
* Statistical summaries

---

## 🔹 5. Data Visualization

Created visualizations using:

* Matplotlib
* Seaborn
* Plotly

### 📊 Visualizations Included

* Bar Charts
* Histograms
* Pie Charts
* Heatmaps
* Trend Analysis
* Severity Distribution Charts
* Interactive Plotly Dashboards

---

# 📸 Project Screenshots

## 🟦 Database Extraction

![Database Extraction](images/database_extraction.png)

---

## 🟩 Data Cleaning

![Data Cleaning](images/data_cleaning.png)

---

## 🟨 Exploratory Data Analysis

![EDA](images/eda.png)

---

## 🟥 Interactive Dashboard

![Dashboard](images/dashboard.png)

---

# 📊 Key Insights

* Identified accident occurrence trends across time periods
* Analyzed severity distributions and accident outcomes
* Detected patterns associated with environmental conditions
* Explored road-condition impacts on accident frequency
* Generated road safety observations through visual analytics
* Created interactive dashboards for exploratory reporting

---

# 🚀 Tech Stack

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| MySQL            | Database Management       |
| SQL              | Data Querying             |
| Python           | Core Programming          |
| Pandas           | Data Manipulation         |
| NumPy            | Numerical Computing       |
| Matplotlib       | Visualization             |
| Seaborn          | Statistical Visualization |
| Plotly           | Interactive Visualization |
| Jupyter Notebook | Development Environment   |

---

# 📁 Project Structure

```text
accident-intelligence-platform/
│
├── notebooks
│
├── images/
│   ├── database_extraction.png
│   ├── data_cleaning.png
│   ├── eda.png
│   └── dashboard.png
│
├── requirements.txt
├── README.md
├── .gitignore
└── LICENSE
```

---

# ⚙️ Installation

```bash
git clone https://github.com/Rider-04/accident-intelligence-platform.git
cd accident-intelligence-platform
pip install -r requirements.txt
```

---

# ▶️ Running the Project

Start Jupyter Notebook:

```bash
jupyter notebook
```

Execute notebooks in sequence from the notebooks directory.

---

# 📦 Requirements

```text
pandas
numpy
matplotlib
seaborn
plotly
mysql-connector-python
jupyter
```

---

# 💡 Key Learnings

* SQL-based data extraction
* MySQL database integration with Python
* Data translation and standardization
* Exploratory Data Analysis
* Statistical visualization
* Interactive dashboard creation
* End-to-end analytics workflow development
* Data storytelling and insight generation

---

# 🚀 Future Improvements

* Accident Severity Prediction Models
* Geospatial Accident Mapping
* Streamlit Analytics Dashboard
* Automated ETL Pipelines
* Real-Time Data Processing
* Predictive Risk Analytics
* Advanced Statistical Modeling

---

# 👨‍💻 Author

## Parth Sharma

Aspiring Data Analyst | Python | SQL | Power BI | Data Visualization

---

# ⭐ If you found this project useful, consider giving it a star!
