# LinkedIn Job Trend Analysis

## 1. Introduction
The job market changes continuously, and students often find it difficult to identify the skills required for their desired roles. This project analyzes job vacancy data to understand the skills, experience levels, locations, and companies associated with job postings. It focuses particularly on Data Analyst job requirements to help students understand which technical skills to prioritize.

## 2. Abstract
LinkedIn Job Trend Analysis is a data analytics project that examines job vacancy and skill datasets to identify frequently required skills and patterns in job postings. Using Python, Pandas, Matplotlib, and Seaborn, the project combines vacancy and skill information, analyzes Data Analyst skill requirements, groups jobs by experience requirements, and explores job locations and companies. Visualizations, including bar charts and a skill-versus-role heatmap, present the findings clearly. The analysis identifies SQL as the most frequently listed skill among Data Analyst postings in the selected dataset, followed by Python, Tableau, Excel, and Power BI. The project demonstrates how data analysis can help students make informed decisions about skill development and career preparation.

## 3. Tools Used
- **Programming language:** Python
- **Data analysis:** Pandas
- **Visualization:** Matplotlib and Seaborn
- **Development environment:** Jupyter Notebook in Visual Studio Code
- **Data format:** CSV

## 4. Steps / Methodology
1. **Data collection:** Obtained a job skills dataset from Kaggle.
2. **Data loading:** Loaded vacancy, skill, and vacancy-skill CSV files using Pandas.
3. **Data preparation:** Cleaned job titles and location values and combined related datasets using merge operations.
4. **Skill analysis:** Counted the most frequently listed skills in Data Analyst job postings.
5. **Experience analysis:** Grouped job postings by years of experience.
6. **Location and company analysis:** Identified commonly occurring job locations and company names.
7. **Visualization:** Created charts for Data Analyst skills, job locations, companies, and experience requirements, along with a skill-versus-role heatmap.
8. **Export:** Saved analysis tables and visualizations in the project output folder.

## 5. Conclusion
The project demonstrates how Python-based data analysis can reveal useful patterns in job vacancy data. SQL, Python, Tableau, Excel, and Power BI were among the most frequently listed skills in the analyzed Data Analyst postings. The results can help students prioritize technical skills when preparing for Data Analyst roles. However, missing and generic values in the dataset should be considered when interpreting the findings.