# 🎓Data Analytics Course Outline
Format: 4 Months → 16 Weeks
Pace: 4–6 hours/week of theory, coding labs, projects
Tools Used: Python, SQL, Excel, Jupyter, Power BI, Git, Scikit-learn, Pandas, NumPy, Tableau (optional)
Project-Based: Each month ends with a real-world project.
---
# 📅 Month 1 – Foundations of Data Analysis
## Week 1: Introduction to Data Analytics
## Lesson Objectives
After completing this course you will be able to:
Explain what Data Analytics is and the key steps in the Data Analytics process.
Differentiate between different data roles such as Data Engineer, Data Analyst, Data Scientist, Business Analyst, and Business Intelligence Analyst.
Describe the different types of data structures, file formats, and sources of data.
Explain the use for different types of data repositories, the ETL process, and Big Data platforms.
Describe the process and tools for gathering data, wrangling data, mining and analyzing data, and visualizing data.
List the different career opportunities in Data Analysis and resources for getting skilled in this domain.
Demonstrate your understanding of gathering, wrangling, mining, analyzing, and visualizing data.

## Lesson Syllabus
Module 1: Modern Data Ecosystem and the Role of Data Analytics

Modern Data Ecosystem 
Key Players in the Data Ecosystem
Defining Data Analysis 
Data Analytics vs. Data Analysis
Module 2: The Data Analyst Role

Responsibilities of a Data Analyst 
A Day in the Life of a Data Analyst 
Module 3: The Data Ecosystem and Languages for Data Professionals

Overview of the Data Analyst Ecosystem
Types of Data  
Understanding Different Types of File Formats
Sources of Data Using Service Bindings
Languages for Data Professionals
Module 4 - Understanding Data Repositories and Big Data Platforms

RDBMS
NoSQL
Data Marts, Data Lakes, ETL, and Data Pipelines
Foundations of Big Data
Big Data Processing Tools
Module 5: Gathering Data

Identifying Data for Analysis
Data Sources
How to Gather and Import Data 
Module 6: Wrangling Data

What is Data Wrangling?
Tools for Data Wrangling
Data Cleaning 
Module 7: Analyzing and Mining Data

Overview of Statistical Analysis
What is Data Mining?
Tools for Data Mining 
Module 8: Communicating Data Analysis Findings

Overview of Communicating and Sharing Data Analysis Findings
Introduction to Data Visualization
Introduction to Visualization and Dashboarding Software
Module 9: Opportunities and Learning Paths

Career Opportunities in Data Analysis
The Many Paths to Data Analysis

Analysis VS Analytics
To analyze is to EXAMINE, looking at information or details within the said data set.
Analytics means using a defined system, tools and techniques 

 # The 7 Key Phases of the analytics lifecycle
 1. Define the problem
 2. Data Collection
 3. Data Preparation
 4. Data Exploration
 5. Modelling & Analysis
 6. Deployment
 7. Monitoring & Optimization
    ## Defining Problems
GOAL: Frame a clear, specific and measurable business question
Steps involved: 
1. Meet with the stakeholders
2. Define KPI( Key Performance Indicators)
3. Understand the business context
   

    ## Data Collection
   GOAL: Gather the right set of data that answers the question
   Internal: CRM, ERP, Website logs, databases
   (CRM: Customer Relationship Management)
   A CRM system is one that helps a business manage interactions with customers and track sale, marketing and support activities.
   .Store Customer Information
   .Manages sales pipelines and leads
   .Track customer support tickets
   .Automate email marketing
   .Analyze customer behavior
   ## Tools:
   * Salesforce
   * Hubspot
   * Zoho
   * MS Dynamics 365
   * Pipedive

     ## (ERP= Enterprise Resource Planning)
     Integrates all the business processes (Like finance, supply chain, HR, inventory, Manufacturing etc) into one platform
     Provide Accounting and financial records
     Inventory and order management
     Data about HR
     Procurement and Supply chain
     Manufacturing and Logistics
  
        External: APIs, Survey, Market reports

   Tools: SQL, Python, ETL tools, Google Analytics, Mixpanel, Segment.
   GOAL: Create a relevant, accurate, timely, and accessible data.
     
     ## Data Preparation
     Goal: Clean and format the data for a smooth analysis
     Tasks: Generate and handle missing values
     Remove duplicates
     Convert formats (eg dates, currencies etc)
     Normalize or encode the data

     TOOLS:
     Python (Pandas, NumPy)
     Excel, Power Query

     Data Exploration (EDA)
   Goal:Uncover patterns, trends and anomalies
   TEchniques:
   Summary statistics (Mean Median and Mode)
   Correlation Matrices
   Data Visualization (Histograms, Scatter plots, box plots)

   Tools:
   Python (Mathplotlib, Seaborn, Plotly)
   Tableau, Power BI

   ## Modeling and Analysis
   Build statistical or machine learning models to derive insights or predictions
   Types of Analysis
   1. Descriptive: What happened?
   2. Diagnostic: Why did it happen?
   3. Predictive: What might happen?
   4. Prescriptive: What should we do?
      Tools:
      Python
      SQL
      Excel
      
   ## Deployment
   Goal: Put the analysis and model into action
   EX:
Embed dashboards into business workflows
Deploy ML Models to production (..APIs)
Send automated alerts or reports

Tools:
Tableau, Power BI(Dashboards)
FastAPI
git, Azure/AWS (for scaling)

## Monitoring & Optimization
Goal: Track outcomes, refine models, and update strategies
Activities:
Monitor KPI
Track model drift
collect user feedback
schedule data pipeline checks
Tools:
Datadog, Grafana
Crin jobs, Airflow
MLflow for tracking ML models

---

## Week 2: Excel & Google Sheets for Analysts
1. Data types, formatting, cleaning

Formulas, functions (VLOOKUP, INDEX-MATCH, etc.)

Pivot tables and basic charts

Excel / Google Sheets for Analytics
Data entry, formatting, filtering, sorting

Basic formulas (SUM, AVERAGE, IF, VLOOKUP, etc.)

Pivot tables

Basic charts and dashboards:

## Data Types and Data Entry:
Basic Shortcut Keys in Exceel

| Action             | Shortcut   |
| ------------------ | ---------- |
| **New workbook**   | `Ctrl + N` |
| **Open workbook**  | `Ctrl + O` |
| **Save workbook**  | `Ctrl + S` |
| **Print**          | `Ctrl + P` |
| **Undo**           | `Ctrl + Z` |
| **Redo**           | `Ctrl + Y` |
| **Cut**            | `Ctrl + X` |
| **Copy**           | `Ctrl + C` |
| **Paste**          | `Ctrl + V` |
| **Select all**     | `Ctrl + A` |
| **Find**           | `Ctrl + F` |
| **Replace**        | `Ctrl + H` |
| **Close workbook** | `Ctrl + W` |


🔹 Navigation

| Action                          | Shortcut           |
| ------------------------------- | ------------------ |
| Move to next cell               | `Arrow keys`       |
| Move to next sheet              | `Ctrl + Page Down` |
| Move to previous sheet          | `Ctrl + Page Up`   |
| Move to the edge of data region | `Ctrl + Arrow key` |
| Jump to cell A1                 | `Ctrl + Home`      |
| Jump to last used cell          | `Ctrl + End`       |
| Go to specific cell             | `Ctrl + G` or `F5` |


🔹 Cell Formatting

| Action              | Shortcut           |
| ------------------- | ------------------ |
| Bold                | `Ctrl + B`         |
| Italic              | `Ctrl + I`         |
| Underline           | `Ctrl + U`         |
| Format cells dialog | `Ctrl + 1`         |
| Add border          | `Ctrl + Shift + &` |
| Remove border       | `Ctrl + Shift + _` |
| Center alignment    | `Alt + H + A + C`  |
| Left alignment      | `Alt + H + A + L`  |
| Right alignment     | `Alt + H + A + R`  |
| Wrap text           | `Alt + H + W`      |
| Merge cells         | `Alt + H + M + C`  |


🔹 Data Entry & Editing

| Action                             | Shortcut           |
| ---------------------------------- | ------------------ |
| Edit active cell                   | `F2`               |
| Enter current date                 | `Ctrl + ;`         |
| Enter current time                 | `Ctrl + Shift + ;` |
| Fill down from cell above          | `Ctrl + D`         |
| Fill right from left cell          | `Ctrl + R`         |
| Insert comment (note in new Excel) | `Shift + F2`       |
| Clear content                      | `Delete`           |
| Add new line within cell           | `Alt + Enter`      |
| Cancel entry                       | `Esc`              |



🔹 Row and Column Operations

| Action               | Shortcut           |
| -------------------- | ------------------ |
| Insert row           | `Ctrl + Shift + +` |
| Delete row           | `Ctrl + -`         |
| Select entire row    | `Shift + Space`    |
| Select entire column | `Ctrl + Space`     |
| Hide selected row    | `Ctrl + 9`         |
| Unhide row           | `Ctrl + Shift + 9` |
| Hide selected column | `Ctrl + 0`         |
| Unhide column        | `Ctrl + Shift + 0` |

🔹 Working with Formulas

| Action                     | Shortcut     |
| -------------------------- | ------------ |
| Start a formula            | `=`          |
| Insert function dialog     | `Shift + F3` |
| Toggle absolute reference  | `F4`         |
| Calculate active worksheet | `Shift + F9` |
| AutoSum                    | `Alt + =`    |
| Display formulas           | `Ctrl + ~`   |


🔹 Tables, Charts, and Filters

| Action                      | Shortcut           |
| --------------------------- | ------------------ |
| Insert table                | `Ctrl + T`         |
| Apply filter                | `Ctrl + Shift + L` |
| Create chart from selection | `Alt + F1`         |
| Insert chart                | `F11`              |

🔹 Other Useful Shortcuts

| Action                 | Shortcut            |
| ---------------------- | ------------------- |
| Open right-click menu  | `Shift + F10`       |
| Display context menu   | `Alt + Shift + F10` |
| Open help              | `F1`                |
| Spell check            | `F7`                |
| Recalculate all sheets | `F9`                |


---




2.  Statistics & Probability Essentials
Types of data (nominal, ordinal, interval, ratio)

Measures of central tendency (mean, median, mode)

Measures of dispersion (variance, standard deviation)

Probability, distributions (normal, binomial)

Correlation vs causation

---
Lookup Functions
-> LookUp functions, searches for a value in the first column of a 
range/table and returns a value from another column in same row.

syntax:  
=VLOOKUP(lookup_value, table_array, col_index_num, [range_lookup])
-> lookup_value : Value searched for--

-> table_array : the data range
-> col_index_num : The column num in the range to return
[range_lookup] : TRUE (approximate match) , FALSE (exact match)











---
## Week 3: Introduction to SQL
Relational databases

SELECT, WHERE, ORDER BY, LIMIT

Aggregate functions and GROUP BY

Joins (INNER, LEFT, RIGHT)

Aggregations and subqueries

Working with dates and NULLs

2.  Data Visualization Basics
Principles of effective charts

Types of visualizations: bar, line, pie, scatter, histogram

Intro to tools: Tableau Public or Power BI (basic dashboards)
---
## Week 4: SQL Advanced Techniques
Subqueries

Window functions (RANK, ROW_NUMBER)

CTEs (Common Table Expressions)

SQL project: Analyze sales database

🛠️ Mini Project: Analyze customer churn from a CSV and SQL database.

# 📅 Month 2 – Python for Data Analysis
## Week 5: Python Essentials
Python syntax, data types, control structures

Functions and modules

Working with files and CSV

## Week 6: Data Manipulation with Pandas
Series vs DataFrames

Reading/writing data

Filtering, sorting, grouping

Handling missing data

## Week 7: Data Cleaning & Wrangling
Tidy data principles

String manipulation

Dealing with duplicates, outliers

Regex basics

## Week 8: Data Visualization with Python
Matplotlib & Seaborn

Plot types: bar, scatter, histogram, heatmaps

Creating dashboards in Jupyter Notebooks

🛠️ Mini Project: Analyze COVID-19 global trends using Pandas and visualizations.

# 📅 Month 3 – Statistics & Exploratory Data Analysis
## Week 9: Applied Statistics for Analysts
Types of data & scales

Mean, median, mode, variance, standard deviation

Probability distributions

## Week 10: Hypothesis Testing
Null & alternative hypothesis

T-test, chi-square test

p-values, confidence intervals

## Week 11: Exploratory Data Analysis (EDA)
Outlier detection

Correlation analysis

Feature relationships

## Week 12: Time Series & Trend Analysis
Time series basics

Moving averages

Seasonality and decomposition

## 🛠️ Mini Project: Perform full EDA on a sales dataset; identify trends and make recommendations.

# 📅 Month 4 – Machine Learning & Business Intelligence
## Week 13: Introduction to Machine Learning
Supervised vs unsupervised learning

Regression (Linear, Logistic)

Model evaluation (RMSE, R2, accuracy, confusion matrix)

## Week 14: Clustering and Classification
K-means clustering

Decision Trees

Scikit-learn workflow

## Week 15: Business Intelligence Tools
Power BI or Tableau basics

Dashboards, filters, slicers

Connecting BI to SQL and Excel

## Week 16: Capstone Project Week
Choose one:

Predicting housing prices

Sales forecasting dashboard

Customer segmentation analysis

Present findings with visualizations and insights

# 🎓 Final Deliverables
Capstone project report (notebook + dashboard)

GitHub portfolio with all notebooks and projects

Resume-ready certification or summary
---
Python (Pycharm)
SQL
Tableau
Power BI
---
# POSTGRESQL DATAABASE

# PostgreSQL Query Guide

This guide is based on a tutorial video and expands its content into a structured mini‑tutorial with explanations and examples.

---

## Table of Contents
1. [Introduction / Setup](#1-introduction--setup)
2. [Basic SELECT](#2-basic-select)
3. [SELECT DISTINCT](#3-select-distinct)
4. [COUNT](#4-count-and-countdistinct)
5. [WHERE Filters](#5-where-filters)
6. [ORDER BY](#6-order-by)
7. [LIMIT](#7-limit)
8. [BETWEEN and IN](#8-between-in)
9. [LIKE / ILIKE](#9-pattern-matching-like--ilike)
10. [Aggregate Functions & GROUP BY](#10-aggregate-functions--group-by)
11. [HAVING](#11-having)
12. [Aliasing (AS)](#12-aliasing-as)
13. [Practice / Challenge Queries](#13-combined--challenge-queries)
14. [Summary Table](#summary-table)

---

## 1. Introduction / Setup

Install PostgreSQL & pgAdmin, then create a database and sample table:

```sql
CREATE TABLE sales (
  sale_id SERIAL PRIMARY KEY,
  product VARCHAR,
  region VARCHAR,
  amount NUMERIC,
  sale_date DATE
);

INSERT INTO sales (product, region, amount, sale_date) VALUES
  ('Widget', 'North', 100, '2025-01-10'),
  ('Gadget', 'South', 150, '2025-01-11'),
  ('Widget', 'North', 120, '2025-01-12'),
  ('Thingamajig', 'North', 80, '2025-02-01'),
  ('Gadget', 'North', 200, '2025-02-05'),
  ('Widget', 'South', 130, '2025-02-10');
```

---

## 2. Basic SELECT

```sql
SELECT product, amount FROM sales;
SELECT * FROM sales;
SELECT product, amount * 1.2 AS adjusted_amount FROM sales;
```

---

## 3. SELECT DISTINCT

```sql
SELECT DISTINCT product FROM sales;
SELECT DISTINCT product, region FROM sales;
```

---

## 4. COUNT and COUNT(DISTINCT)

```sql
SELECT COUNT(*) AS total_sales FROM sales;
SELECT COUNT(region) AS region_count FROM sales;
SELECT COUNT(DISTINCT product) AS distinct_products FROM sales;

SELECT region, COUNT(*) AS sales_in_region
FROM sales
GROUP BY region;
```

---

## 5. WHERE Filters

```sql
SELECT * FROM sales WHERE amount > 100;

SELECT product, amount
FROM sales
WHERE region = 'North' AND sale_date >= '2025-02-01';
```

---

## 6. ORDER BY

```sql
SELECT product, amount FROM sales ORDER BY amount DESC;
SELECT product, region, amount FROM sales ORDER BY region ASC, amount DESC;
```

---

## 7. LIMIT

```sql
SELECT * FROM sales ORDER BY amount DESC LIMIT 3;
```

---

## 8. BETWEEN / IN

```sql
SELECT * FROM sales WHERE amount BETWEEN 100 AND 150;
SELECT * FROM sales WHERE region IN ('North', 'South');
```

---

## 9. Pattern Matching: LIKE / ILIKE

```sql
SELECT * FROM sales WHERE product LIKE 'W%';
SELECT * FROM sales WHERE product LIKE '%get';
SELECT * FROM sales WHERE product ILIKE '%widget%';
```

---

## 10. Aggregate Functions & GROUP BY

```sql
SELECT region, SUM(amount) AS total_sales
FROM sales
GROUP BY region;

SELECT region,
       SUM(amount) AS total_sales,
       AVG(amount) AS avg_sale,
       COUNT(*) AS count_sales,
       MAX(amount) AS max_sale,
       MIN(amount) AS min_sale
FROM sales
GROUP BY region;
```

---

## 11. HAVING

```sql
SELECT region, COUNT(*) AS cnt
FROM sales
GROUP BY region
HAVING COUNT(*) > 2;

SELECT region, SUM(amount) AS total_sales
FROM sales
GROUP BY region
HAVING SUM(amount) > 200;
```

---

## 12. Aliasing (AS)

```sql
SELECT product AS prod, SUM(amount) AS total_amt
FROM sales AS s
GROUP BY product;
```

---

## 13. Combined / Challenge Queries

```sql
-- Top product by total sales
SELECT product, SUM(amount) AS total_sales
FROM sales
GROUP BY product
ORDER BY total_sales DESC
LIMIT 1;

-- Regions with average sale amount > 120
SELECT region, AVG(amount) AS avg_sale
FROM sales
GROUP BY region
HAVING AVG(amount) > 120
ORDER BY avg_sale DESC;

-- Distinct products per region
SELECT region, COUNT(DISTINCT product) AS num_products
FROM sales
WHERE region = 'North'
GROUP BY region;

-- Sales between certain dates
SELECT product, SUM(amount) AS total_sales
FROM sales
WHERE sale_date BETWEEN '2025-01-01' AND '2025-02-28'
  AND region IN ('North', 'South')
GROUP BY product
ORDER BY total_sales DESC;
```

---

## Summary Table

| Clause / Concept | Level | Purpose |
|------------------|-------|---------|
| `SELECT` | Row / projection | Choose columns or expressions |
| `DISTINCT` | Row | Remove duplicate rows |
| `WHERE` | Row | Filter rows |
| `GROUP BY` | Group | Group rows for aggregation |
| Aggregate functions | Group | SUM, AVG, COUNT, etc. |
| `HAVING` | Group | Filter groups after aggregation |
| `ORDER BY` | Final | Sort results |
| `LIMIT` | Final | Restrict number of rows |
| `BETWEEN`, `IN` | Row | Range / set filters |
| `LIKE` / `ILIKE` | Row | Pattern matching |
| `AS` | Row/Group | Alias for readability |

---

