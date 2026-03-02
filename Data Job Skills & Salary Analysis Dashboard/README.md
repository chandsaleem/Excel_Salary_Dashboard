# 📊 Data Job Skills & Salary Analysis Dashboard (Excel + Power Query)

This project is an interactive Excel dashboard designed to help users analyze **which skills are most valuable in data jobs** and **how those skills influence salary ranges**.  
By selecting a job title (e.g., Data Engineer, Data Analyst, Data Scientist), the dashboard dynamically updates to show:

- The **average yearly salary** associated with each skill  
- The **number of job postings** that mention that skill  
- A combined visual that highlights both **skill demand** and **salary impact**

This enables job seekers, analysts, and career planners to identify which skills are most rewarding and where to focus their learning efforts.

---

## ⭐ Project Purpose

The goal of this dashboard is to answer two essential questions:

1. **Which skills are most in-demand for a given data job?**  
2. **Which skills are associated with higher salaries?**

By combining skill frequency with salary averages, users can quickly identify:

- High‑value skills  
- High‑demand skills  
- Skills that offer both strong salary potential and high job availability  

This makes the dashboard a practical tool for career planning and skill prioritization.

---

## 🧩 How the Dashboard Works

### 1. Power Query for ETL

Power Query was used to perform all data preparation tasks:

- Imported multiple datasets from different sources  
- Cleaned and standardized column names  
- Merged tables into a unified dataset  
- Removed duplicates and null values  
- Normalized job titles and skill fields  

This created a clean, analysis‑ready dataset for the dashboard.

---

### 2. PivotTables for Analysis

PivotTables were used to compute:

- **Skill Count**  
  Number of job postings that mention each skill for the selected job title.

- **Average Salary**  
  The average yearly salary for postings requiring that skill.

These metrics form the analytical foundation of the dashboard.

---

### 3. Interactive Slicer

A slicer allows users to filter the dashboard by job title, such as:

- Data Engineer  
- Data Analyst  
- Data Scientist  
- Machine Learning Engineer  
- Business Analyst  
- Cloud Engineer  
- Senior-level roles  

Selecting a job title updates the PivotTable and chart instantly.

---

### 4. Combined Chart (Bar + Line)

The dashboard includes a dual‑axis chart:

- **Bars** → Skill Count  
- **Line** → Average Salary  

This combination makes it easy to compare:

- How often a skill appears in job postings  
- How much salary uplift that skill provides  

Users can visually spot skills that are both **high‑demand** and **high‑paying**.

---

## 📊 Example Insight (Data Engineer)

When selecting **Data Engineer**, the dashboard reveals:

- **SQL** and **Python** appear in the highest number of job postings  
- **Python**, **Excel**, and **R** show the highest average salaries  
- Cloud skills like **AWS** and **Azure** also rank strongly in both salary and demand  

This helps users understand which skills to prioritize for maximum career impact.

---

## 🛠️ Tools & Techniques Used

### Excel Features
- PivotTables  
- PivotCharts  
- Slicers  
- Dual‑axis charts  
- Custom formatting  
- Data modeling  

### Power Query
- Data import  
- Merging multiple tables  
- Cleaning and transforming data  
- Building a unified dataset  

### Data Analysis Logic
- Grouping by job title  
- Counting skill occurrences  
- Calculating average salary per skill  
- Dynamic filtering with slicers  

---


---

## 🚀 How to Use the Dashboard

1. Open the Excel dashboard file  
2. Use the slicer to select a job title  
3. The PivotTable and chart update automatically  
4. Analyze:
   - Skill demand  
   - Salary impact  
   - High‑value skills  
   - Skill gaps  

This makes it easy to plan your learning path or evaluate job market trends.

---

## 🔮 Future Enhancements

- Add regional salary filters  
- Add trend analysis over time  
- Add skill difficulty ratings  
- Add a “Top 5 Skills to Learn” recommendation engine  

---

## 🙌 Acknowledgements

Dataset provided by **Luke Barousse** as part of his Data Jobs 2023 project.  
This dashboard was built to strengthen my skills in:

- Excel analytics  
- Power Query ETL  
- Data visualization  
- Career‑focused data storytelling  

---


