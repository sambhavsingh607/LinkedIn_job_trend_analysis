# LinkedIn Job Trend Analysis

## Overview
This project analyzes LinkedIn job postings to identify trending skills across different cities and job roles using Python and data visualization.

## Objective
- Collect or simulate LinkedIn job data (title, company, skills, location)
- Clean and parse skill information using Pandas
- Generate visualizations showing top in-demand skills by city
- Derive insights about job market demand trends

## Tools Used
- Python
- BeautifulSoup
- Pandas
- Matplotlib / Seaborn
- Jupyter Notebook (Anaconda)

## Steps Performed
1. Created mock LinkedIn job data and saved it as `data/mock_jobs.csv`
2. Cleaned and parsed skill tags using Pandas
3. Counted skill frequencies and grouped data by city
4. Generated two main visualizations:
   - Bar chart of top 10 skills
   - Heatmap showing skills by city
5. Saved output images in the `visuals` folder

## Folder Structure
LinkedIn_Job_Trend_Analysis/
│
├── data/
│   └── mock_jobs.csv
│
├── visuals/
│   ├── skill_heatmap.png
│   └── top_skills_chart.png
│
├── linkedin_scraper.ipynb
└── README.md

## Conclusion
This mini project demonstrates how Python can be used to analyze job market trends through data scraping and visualization. It provides insight into the most in-demand skills and cities, and can be extended to real-time LinkedIn data in future versions.
