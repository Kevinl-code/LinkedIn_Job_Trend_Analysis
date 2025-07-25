# 📊 LinkedIn Job Trend Analysis (Web Scraping)

This project analyzes job posting trends from LinkedIn data to uncover the most in-demand skills across various **cities** and **job roles**.

## 🧠 Objective
To visualize and understand how job skill requirements vary by **location** and **job title** using real-world job posting data.

## 🛠 Tools & Technologies
- **Python**
  - `Pandas` – Data manipulation
  - `BeautifulSoup` – Web scraping (or use exported HTML data)
  - `Matplotlib` / `Seaborn` – Visualization
- **Excel** – Optional data export
- **Jupyter Notebook**

## 📁 Dataset
A CSV file (`Job_Postings.csv`) containing:
- `Job Title` – e.g., Data Analyst, Backend Developer
- `Skills` – Comma-separated values (e.g., Python, SQL, Excel)
- `City` – Location of the job

> 📌 *Note: Due to LinkedIn scraping restrictions, data is assumed to be exported manually or synthetically generated for demonstration.*

## 🔍 Features
- ✅ Skill extraction and cleaning
- ✅ Heatmap of top 10 skills across cities
- ✅ Skill vs Role matrix visualization
- ✅ Job demand recommendations based on selected skills

## 📊 Visualizations
- **City-Skill Heatmap**: Understand regional demand
- **Role-Skill Matrix**: Understand how skills align with roles
- **Skill-Based Recommendations**: Find top cities and jobs for a given skill
