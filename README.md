# OOP Data Science Scrapping Project
### 📚 University Project – Object-Oriented Programming CA

This project was completed during my **second year** of the **BSc in Mathematics and Data Science** at **Dundalk Institute of Technology**, as part of the continuous assessment for the **Object-Oriented Programming** module. The objective The objective of this project was to build a fully automated web scraping pipeline to extract live job listings in the field of Data Science from a selected website, clean the data, and store it in a structured relational database for easy querying.

---

## 📌 Project Overview

The objective of this project was to build a fully automated web scraping pipeline to extract live job listings in the field of Data Science from a selected website, clean the data, and store it in a structured relational database for easy querying.

Key tasks include:

- Identifying and investigating a suitable website for scraping (e.g., IrishJobs, Reed, etc.)
- Scraping job data using BeautifulSoup and Requests (or Selenium when necessary)
- Parsing and cleaning the collected data using Pandas
- Storing the final dataset in a MySQL database using a normalised schema

---
## 🔍 Data Collected
The website used for collection is Morgan McKinley, which is an Irish website for Irish jobs.

The script collects and stores the following data:

- Job Title
- Location (City or Region)
- Date Listed
- Salary (or Salary Range, if available)
- Job Type
- Other relevant job specification fields (where available)

This is a **simple student project** — it does not include advanced validation, security, or styling.
