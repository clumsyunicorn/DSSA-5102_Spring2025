# 📘 DSSA-5102: Data Gathering & Warehousing (Spring 2025)

_Data Science and Strategic Analytics Graduate Program_  
**Stockton University**

---

## 📁 Repository Overview

This repository contains assignments and cleaned datasets for **DSSA-5102 - Data Gathering & Warehousing**. The course emphasizes real-world data collection, cleaning, transformation, and warehousing using Python and SQL. Each assignment builds upon the last, culminating in a live API connection and populated MySQL database.

---

## 💻 Languages & Environment
- **Languages:** Python, SQL
- **Tools:** Jupyter Notebook, Anaconda Navigator, GitHub, MySQL Workbench, Spyder

---

## 📦 Datasets

### 1. Data Science Salaries Dataset (`ds_salaries_clean.csv`)
- **Source:** [Kaggle - Data Science Salaries](https://www.kaggle.com/datasets/ruchi798/data-science-job-salaries)
- **Accessed On:** January 25, 2025
- **Year Range:** 2020–2023
- **Cleaning Process:**
  - Removed null values
  - Normalized currencies to USD
  - Simplified column names
  - Removed outliers using IQR
- **Units:**
  - Salary in USD
  - Experience: EN (Entry), MI (Mid), SE (Senior), EX (Executive)

### 2. Global Internet Users Dataset (`internet_users.csv`)
- **Source:** [World Bank Data](https://data.worldbank.org/indicator/IT.NET.USER.ZS)
- **Accessed On:** February 2, 2025
- **Year Range:** 1990–2022
- **Cleaning Process:**
  - Removed rows with missing data
  - Converted percentages to decimal
  - Reformatted year column
- **Units:** Internet usage as % of population

### 3. Palmer Penguins Dataset (`penguins_clean.csv`)
- **Source:** [palmerpenguins R package](https://allisonhorst.github.io/palmerpenguins/)
- **Accessed On:** March 5, 2025
- **Cleaning Process:**
  - Removed rows with missing values
  - Standardized numerical fields
- **Units:** Bill length/depth (mm), body mass (g), flipper length (mm)

---

## 📚 Assignments

### Assignment #1: Locating a Dataset
- Selected initial datasets
- Explored structure and source reliability
- Described dataset origin and license

### Assignment #2: Cleaning our Dataset
- Performed null removal, type conversion, and outlier filtering
- Included code comments to explain each cleaning step

### Assignment #3: Metadata
- Created this README file
- Added source, units, transformation logic for each dataset

### Assignment #4 & #5: Only Murders in the...Database?
- Practiced `WHERE`, `GROUP BY`, and basic SQL filters
- Answered mystery-style questions using data insights

### Assignment #6: Creating a Database from Scratch
- Created tables in MySQL Workbench
- Populated tables using Python and `pymysql`
- Linked foreign keys and tested table integrity

---

## 🧩 Advanced Assignments

### Assignment #7: Creating our Database Schema Diagram
- **Tools Used:** Python, MySQL Workbench, Jupyter Notebook  
- **Summary:** Finalized the full schema and visualized using MySQL EER Diagram tools. Uploaded `.ipynb` with schema SQL and screenshots.

### Assignment #8: JOINing our Knowledge
- **Tools Used:** SQL, Python  
- **Summary:** Performed `INNER`, `LEFT`, and `FULL` JOINs to answer multi-table queries.  
- **Output:** Markdown cells include rationale and query logic.

### Assignment #9: MISC. SQL Syntax and Longer Queries
- **Tools Used:** SQL, Jupyter Notebook or Workbench  
- **Summary:** Explored `CASE`, nested `SELECT`, aliases, and advanced filters. Exported results to `.csv`. Markdown answers and explanations included.

### Assignment #10: API/Live Social Media Data – Pulling it All Together!
- **Tools Used:** Python, ipyNaturalist, iNaturalist API  
- **Summary:** Accessed turtle observation data using either:
  - A personal API token, or  
  - Instructor's public profile (`melissalaurino`)
- **Result:** Data pulled, transformed, loaded into MySQL; visualized insights and submitted as `.ipynb`

---

## 🛠 Additional Notes
- Markdown cell questions have now been fully answered.
- All notebooks now include inline code comments for better clarity.
- All assignment `.ipynb` files are available on GitHub.

---

## 🔗 Links
- **GitHub Account:** [clumsyunicorn](https://github.com/clumsyunicorn)
- **Repository:** [DSSA-5102 Spring 2025](https://github.com/clumsyunicorn/DSSA-5102_Spring2025)

---

_Last updated: May 2, 2025_
