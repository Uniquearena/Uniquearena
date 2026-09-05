# Hi, I'm Ansh Gupta 👋

<!--
HOW TO USE THIS FILE:
1. Create a new PUBLIC repo named exactly: Uniquearena  (must match your username)
2. Add this file as README.md in that repo's root
3. Add the project-banners/ folder (4 real dashboard screenshots) to the same repo,
   same location as this README
4. GitHub will automatically show it at the top of your profile page
-->

<div align="center">

### 📊 Data Analyst | SQL · Power BI · Python — with hands-on ML & GenAI

Turning raw tables into decisions.

</div>

B.Tech IT student at Jaypee University of Information Technology (grad. May 2026), with hands-on experience in attrition analysis, ETL pipeline design, and interactive BI dashboards — plus working knowledge of predictive modeling and LLM-powered tools.

- 🔭 **Currently:** Analytics Intern experience at **Coreline Solutions Inc.** — built KPI reporting pipelines that improved accuracy by 45% and saved 15+ hrs/week
- 🌱 **Sharpening:** advanced DAX, statistical hypothesis testing, Python-based EDA, and applied machine learning
- 💼 **Open to:** Data Analyst, Business Intelligence, and Data Analytics roles — also exploring Data Science opportunities
- 📫 **Reach me:** guptaansh0808@gmail.com
- 🌐 **Full portfolio:** **[uniquearena.github.io/portfolio](https://uniquearena.github.io/portfolio)**

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/annshgupta)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=googlechrome&logoColor=white)](https://uniquearena.github.io/portfolio)
[![Gmail](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:guptaansh0808@gmail.com)

### 🛠️ Tech Stack

![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=microsoftsqlserver&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Excel](https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Google_Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)

---

## 📈 Data Analytics Projects

### [Real Estate Market Sales Performance](https://uniquearena.github.io/portfolio/#projects)
`Power BI` `DAX` `Data Modeling`

<img src="project-banners/real_estate.png" width="100%"/>

A 3-page Power BI executive dashboard analyzing regional real estate trends with custom DAX measures — YTD running totals and YoY performance metrics. Isolated the top-performing revenue zone ($95B peak) and identified auction sales as the *only* segment with positive YoY growth (+29%), offsetting a 75% drop in the standard family market.

<br/>

### [Employee & Department SQL Analysis](https://uniquearena.github.io/portfolio/#projects)
`SQL Server` `T-SQL` `Database Design`

Modeled a normalized multi-table schema (Employees, Departments, Salaries) and wrote 50+ T-SQL queries — multi-table JOINs, GROUP BY aggregations, and date/string manipulation. Used window functions (`DENSE_RANK`, `LEAD`/`LAG`) and nested subqueries to map reporting hierarchies and salary brackets while cutting down redundant joins.

<br/>

### [NYC Vehicle Collision Trend Analysis](https://uniquearena.github.io/portfolio/#projects)
`Excel` `PivotTables` `PivotCharts`

<img src="project-banners/nyc_collision.png" width="100%"/>

Cleaned and evaluated 400+ vehicle collision records across NYC boroughs with advanced Excel formulas, PivotTables, and dynamic PivotCharts. Surfaced monthly crash and injury-severity trends, flagging driver inattention as the primary crash catalyst across commercial fleets.

<br/>

### [Car Price Prediction Dashboard](https://uniquearena.github.io/portfolio/#projects)
`Power BI` `Statistical Regression`

<img src="project-banners/car_price_dashboard.png" width="100%"/>

Compared actual vs. predicted MSRP across 1,610 vehicles ($72.5K mean MSRP) using regression curves against horsepower and engine torque. Built multi-attribute parametric slicers so stakeholders can filter pricing variance by make, body class, and drivetrain.

---

## 🤖 Data Science Projects

### [Employee Attrition Prediction](https://github.com/Uniquearena/employee-attrition-prediction)
`Python` `scikit-learn` `XGBoost` `TensorFlow`

Trained and compared 4 classifiers — Logistic Regression, Random Forest, XGBoost, and a Keras deep neural network — on the IBM HR dataset (1,470 employees, 16.1% attrition rate). Logistic Regression came out on top at **91.0% accuracy**, beating even the deep learning model. Diagnosed class imbalance as the real limitation: minority-class ("left") recall sat at 0.55 vs. 0.93 for the majority class, with resampling and threshold-tuning flagged as next steps.

<br/>

### [Zomato Restaurant Rating Prediction](https://github.com/Uniquearena/zomato-restaurant-rating-prediction)
`Python` `scikit-learn` `Flask`

<img src="project-banners/zomato_rating.png" width="100%"/>

Cleaned and feature-engineered Zomato restaurant listing data, then trained and compared Linear Regression and Random Forest Regressor models to predict restaurant ratings. Packaged the trained model behind a Flask web app for interactive predictions.

<br/>

### [Flight Price Prediction](https://github.com/Uniquearena/Flight-Price-Prediction)
`Python` `CatBoost` `Flask`

Engineered date, time, and route features from airline booking data and trained a CatBoost regression model to predict ticket prices. Deployed the trained model through a Flask web form for real-time price predictions.

---

## ✨ Generative AI Projects

### [Email Improver App](https://github.com/Uniquearena/Email-Improver-App)
`Python` `Streamlit` `Google Gemini API`

Built a Streamlit web app that rewrites user-submitted emails for grammar, structure, and professional tone. Uses a prompt-engineered call to the Google Gemini API, with a structured prompt template designed to preserve the sender's original intent while enforcing consistent, production-ready output.

<br/>

### GenAI Chatbot
*Coming soon — have a repo for this already? Send it my way and I'll add it here.*

---

More case studies — Sales Performance Dashboard, Procurement Spend Analysis, and other EDA notebooks — are in the **[full portfolio](https://uniquearena.github.io/portfolio)**.

### 📊 GitHub Stats

![](https://github-readme-stats.vercel.app/api?username=Uniquearena&theme=dark&hide_border=false&include_all_commits=false&count_private=false)
![](https://github-readme-stats.vercel.app/api/top-langs/?username=Uniquearena&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

---
⭐️ From [Ansh Gupta](https://github.com/Uniquearena) | [Portfolio](https://uniquearena.github.io/portfolio) | [LinkedIn](https://linkedin.com/in/annshgupta)
