# LinkedIn Job Trend Analysis

## 1. Introduction
LinkedIn Job Trend Analysis is a data analytics project that examines job postings to identify the most in-demand skills, job roles, experience requirements, locations, and hiring companies. The goal is to help students and job seekers understand employment trends and prepare for relevant roles.

## 2. Objectives
- Identify the most demanded skills for Data Analyst jobs.
- Analyze job titles and skill requirements.
- Examine experience requirements across job postings.
- Identify common job locations and companies.
- Visualize findings using charts and a skill-versus-role heatmap.

## 3. Dataset
The project uses the **Data Analyst Skills Evolution (2022–2026)** dataset from Kaggle.

Dataset: https://www.kaggle.com/datasets/bohdandanoi/data-analyst-skills-evolution-2022-2026

The dataset contains job vacancy information, skills, and relationships between vacancies and skills.

## 4. Tools and Technologies
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

## 5. Methodology
1. Load the CSV datasets.
2. Clean job titles and location values.
3. Combine vacancy and skill information using merges.
4. Analyze the most frequently required skills.
5. Examine experience requirements, job locations, and companies.
6. Create charts and a skill-versus-role heatmap.
7. Export analysis results and visualizations.

## 6. Key Findings
- SQL is the most frequently listed skill among Data Analyst postings in this dataset.
- Python, Tableau, Excel, and Power BI are also frequently listed.
- Entry-level and zero-year experience categories have substantial representation.
- Job locations and company names contain generic or unknown values, which should be considered when interpreting results.

## 7. Project Structure
- `data/` — Original CSV datasets.
- `outputs/` — Analysis CSV files and chart images.
- `linkedin_job_analysis.ipynb` — Analysis notebook.
- `README.md` — Project documentation.

## 8. Conclusion
This project demonstrates how Python-based data analysis can reveal skill requirements and patterns in job postings. The findings can help students prioritize relevant technical skills when preparing for Data Analyst roles.

## 9. Limitations
The dataset contains missing and generic values, and the available date information is insufficient for a reliable time-trend analysis. The results describe this dataset and may not represent the entire job market.