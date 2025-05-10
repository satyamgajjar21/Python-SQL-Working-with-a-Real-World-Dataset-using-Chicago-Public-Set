<p align="center">
  <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/images/SN_web_lightmode.png" width="300" alt="Skills Network Logo">
</p>

# Working with a Real-World Dataset using SQL and Python

This project demonstrates how to analyze a real-world dataset using SQL within a Jupyter notebook, combined with Python and SQLite. The dataset covers Chicago Public Schools' performance metrics for the academic year 2011–2012.

---

## ⏱ Estimated Time

**30 minutes**

---

## 🎯 Objectives

- Understand the Chicago Public School progress report dataset
- Load and store the dataset in a SQLite database
- Retrieve metadata about tables and columns
- Write SQL queries with filtering, ordering, and aggregation
- Use SQL subqueries and built-in functions
- Work with mixed-case and special-character column names

---

## 📊 Dataset Description

**Source:** [City of Chicago Open Data Portal](https://data.cityofchicago.org/Education/Chicago-Public-Schools-Progress-Report-Cards-2011-/9xs2-f89t)

🔗 [Download the version used in this lab](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DB0201EN-SkillsNetwork/labs/FinalModule_Coursera_V5/data/ChicagoPublicSchools.csv)

The dataset includes:

- School names and types (Elementary, Middle, High)
- Safety score
- Average student attendance (as % string)
- College enrollment
- Community area and demographic indicators

---

## ⚙️ Setup

### Required Python Libraries

```bash
pip install pandas ipython-sql prettytable
