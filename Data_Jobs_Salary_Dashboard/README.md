# Excel_Salary_Dashboard
This data jobs salary dashboard was created to help job seekers investigate salaries for their desired jobs and ensure they are being adequately compensated. 

The data is by Luke Barrousse(Youtuber), which includes data about when the job was posted, Job Title, Average Yearly/Hourly Salary, location, skills required. The analysis is made on these measures.

### Dashboard File
My final dashboard is in [1_Salary_Dashboard.xlsx](1_Salary_Dashboard.xlsx)

![Salary Dashboard](./Salary%20Dashboard.gif)


The following Excel skills were utilized for analysis:

- **📉 Charts**
- **🧮 Formulas and Functions**
- **❎ Data Validation**

- 🔍 **Multi-Criteria Filtering:** Checks job title, country, schedule type, and excludes blank salaries.
- 📊 **Array Formula:** Utilizes `MEDIAN()` function with nested `IF()` statement to analyze an array.
- 🎯 **Tailored Insights:** Provides specific salary information for job titles, regions, and schedule types.
- **🔢 Formula Purpose:** This formula populates the table below, returning the median salary based on job title, country, and type specified.

  The Logic used to get the median:

```
=MEDIAN(
IF(
    (jobs[job_title_short]=A2)*
    (jobs[job_country]=country)*
    (ISNUMBER(SEARCH(type,jobs[job_schedule_type])))*
    (jobs[salary_year_avg]<>0),
    jobs[salary_year_avg]
)
)
```



Checkut the excel file.
