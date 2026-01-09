# Industry Skill Insights
Data-Driven Analysis of Job Market Skill Demand

##  Project Overview
This project analyzes real-world job postings to identify in-demand technical skills, common skill combinations, and differences in skill requirements across job levels.  
The objective is to understand current industry expectations and help align technical skill preparation with market needs.

The project demonstrates an end-to-end data analytics workflow, covering data cleaning, exploratory analysis, SQL validation, business reporting, and visualization.

---

##  Objectives
- Identify the most in-demand technical skills across job postings  
- Analyze common skill combinations such as *Python + SQL  
- Compare skill requirements across job levels
- Validate Python-based insights using SQL  
- Present findings through Excel and Tableau dashboards

---

##  Project Structure
industry-skill-insights/
│
├── data/
│ ├── cleaned_jobs.csv
│ ├── job_postings.csv
│ ├── job_skills.csv
│ └── job_summary.csv
│
├── notebooks/
│ ├── 01_data_cleaning.ipynb
│ ├── 02_skill_eda.ipynb
│ └── 03_sql_analysis.ipynb
│
├── excel/
│ └── industry_skill_analysis.xlsx
│
├── dashboards/
│ ├── industry_skill_dashboard.twbx
│ └── screenshots/
│ └── tableau_dashboard.jpg
│
└── README.md

yaml
Copy code

---

##  Tools & Technologies
- **Python** (Pandas, Matplotlib)  
- **SQLite** (SQL-based analysis)  
- **Microsoft Excel** (Pivot tables for business reporting)  
- **Tableau** (Interactive dashboard & visualization)  
- **Git & GitHub** (Version control)

---

## Analysis Workflow

### 1️⃣ Data Cleaning & Feature Engineering
- Merged multiple job-related datasets  
- Cleaned unstructured job descriptions  
- Extracted skill indicators such as `has_python`, `has_sql`, etc.  
- Created an analysis-ready dataset  

 Notebook: `01_data_cleaning.ipynb`

---

### 2️⃣ Exploratory Data Analysis (Python)
- Overall skill demand analysis  
- Skill combination analysis (e.g., Python + SQL)  
- Skill demand comparison across job levels  
- Insight-driven visualizations  

 Notebook: `02_skill_eda.ipynb`

---

### 3️⃣ SQL Analysis (SQLite)
- Loaded cleaned data into a SQLite database  
- Performed aggregation and filtering using SQL  
- Validated Python-based insights through SQL queries  

 Notebook: `03_sql_analysis.ipynb`

---

### 4️⃣ Excel Analysis
- Created pivot tables to analyze:
  - Skill demand vs job level  
  - Core skill combinations  
- Provided a business-friendly summary for non-technical stakeholders  

File: `excel/industry_skill_analysis.xlsx`

---

### 5️⃣ Tableau Dashboard
An interactive dashboard visualizing:
- Overall skill demand  
- Skill demand by job level  
- Job level filtering  

 Dashboard Preview:

![Tableau Dashboard](dashboards/screenshots/tableau_dashboard.jpg)

---

##  Key Insights
- Excel and SQL are the most demanded skills across job postings  
-Python and Machine Learning show strong demand, especially in senior roles  
- Business Intelligence tools (Tableau / Power BI) are often required alongside core technical skills  
- SQL-based analysis closely aligns with Python-based insights, validating the results  

---

##  Conclusion
This project showcases a complete data analytics pipeline, integrating programming, SQL, business tools, and visualization to derive actionable insights from real-world job data.  
It reflects practical, industry-relevant skills expected from a Computer Science graduate / Data Analyst.

---

## Author
Prajakta Waghmare 
GitHub: https://github.com/prajaktawaghmare13








