# 💼 LinkedIn Job Trend Analysis (Web Scraping)

### 📊 Analyze Skill Demand and Job Trends Across Cities and Roles using Python

---

## 🚀 **Project Overview**

This project focuses on analyzing job market trends by scraping LinkedIn job postings to identify **in-demand skills, roles, and city-based hiring patterns**.  
Using **Python**, **BeautifulSoup**, and **Pandas**, the project automates data extraction, cleaning, visualization, and insight generation — giving a clear view of **which skills are most required for different roles across major cities**.

---

## 🎯 **Objectives**

- Scrape job data (titles, companies, locations, and skills) from LinkedIn.  
- Clean and preprocess raw HTML data using Pandas.  
- Identify top 10 skills per city and visualize trends.  
- Build a **Skill vs Role matrix** to compare demand across job titles.  
- Generate recommendations and insights for job seekers and recruiters.

---

## 🧰 **Tools and Libraries Used**

| Tool / Library | Purpose |
|----------------|----------|
| **Python** | Core programming language |
| **BeautifulSoup** | Web scraping job details |
| **Requests** | Sending HTTP requests |
| **Pandas** | Data cleaning & manipulation |
| **Matplotlib / Seaborn** | Visualizations and heatmaps |
| **Excel** | Data export & reporting |
| **ReportLab** | PDF report generation |

---

## ⚙️ **Project Workflow**

1. **Data Collection**
   - Extract job title, company, location, and skills using BeautifulSoup and Requests.
   - Store scraped data in a structured DataFrame.

2. **Data Cleaning & Preparation**
   - Handle duplicates, missing values, and inconsistent skill tags.
   - Normalize skill names (e.g., “python”, “Python”, and “PYTHON” merged).

3. **Data Analysis**
   - Count frequency of each skill across roles and cities.
   - Create a **Skill**
