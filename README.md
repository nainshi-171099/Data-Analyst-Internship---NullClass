**E-commerce Discount & Rating Analysis – Internship Project**
**📌 Project Overview**

This repository contains all the work I completed as part of my Data Analyst internship.
The project focuses on analysing e-commerce product data to understand:

How discounts relate to customer ratings

How average discounts change over time

Key patterns in price, discount, and rating across different product categories

The repository includes:

🐍 Python scripts for data cleaning, analysis, and visualizations

📊 Power BI dashboard for interactive insights

📝 Documentation/reports in Word (DOC/DOCX) format

📂 Repository Structure
.
├── Python/ # Python files / Jupyter notebooks
├── Power BI/              # Power BI .pbix file
├── Reports/              # Internship reports in .doc/.docx
└── README.md             # Project overview (this file)


**🔧 Tools & Technologies**
Python

pandas, numpy

matplotlib, seaborn

scipy / stats (for correlation, if used)

Power BI

Interactive dashboard with cards, charts, and filters

Other

Git & GitHub

MS Word for report writing

🐍 Python – Tasks Completed
1️⃣ Data Cleaning & Preparation

Imported the dataset into Python.

Handled missing values (e.g., dropped or treated missing Discount and Rating).

Converted columns like Price, Discount, Rating, Date to proper numeric/date formats.

Created a clean copy of the data for analysis.

2️⃣ KPI Calculation

Computed key metrics such as:

Average Price (e.g., around 950)

Average Discount (e.g., around 40%)

Average Rating (e.g., around 3.8)

These KPIs give a quick view of:

Typical price level of products

How aggressive the discounting is

Overall customer satisfaction through ratings

3️⃣ Relationship Between Discount & Rating

To check whether higher discounts lead to higher ratings, I:

Created scatter plots between:

Discount vs Rating

Price vs Discount

Added a trend line to understand the direction of the relationship.

Calculated:

Pearson correlation – to measure linear relationship

Spearman correlation – to measure monotonic relationship

Result (high level):
The analysis showed that higher discounts do not strongly guarantee higher ratings. Ratings seem to be influenced by other factors like product quality, category, and customer expectations.

4️⃣ Outlier & Distribution Analysis (Boxplots)

Created boxplots for:

Price

Discount

Rating

Sometimes broken down by subcategory (if available)

This helped to:

Identify outliers (e.g., extremely high prices or very high discounts)

Understand the spread and typical range of each variable

5️⃣ Time Series – Discount Trend Over Time

Added a scraping date / date column (for example, from 1 Nov to 7 Nov).

Calculated average discount per day.

Plotted a line chart of average discount over time.

Added a moving average (e.g., 3-day) to smooth short-term fluctuations.

This shows how discounting strategy changes over the days and whether there is any pattern (e.g., weekend offers, spikes on certain days).

6️⃣ Category/Subcategory Analysis

Grouped data by subcategory to calculate:

Average price

Average discount

Average rating

Created:

Bar charts – to compare averages across subcategories

Scatter plots by subcategory – to see how discount vs rating behaves for different product types

This helps an e-commerce manager identify:

Which subcategories have high discounts but only average ratings

Which ones offer good ratings even with lower discounts

Where there may be opportunities to improve pricing or promotion strategy

📊 Power BI Dashboard

The Power BI report (in the powerbi/ folder) summarizes the analysis in an interactive way.

Key elements:

KPI Cards

Average Price

Average Discount

Average Rating

Charts

Line chart for average discount trend over time

Bar charts for average price / discount / rating by category or subcategory

Scatter plot visual to show the relationship between discount and rating

Filters/Slicers

By category / subcategory (if available)

By date range

This allows stakeholders to explore the data dynamically and answer business questions quickly.

📝 Reports

The reports/ folder contains:

Internship task-wise reports

Explanation of:

Data cleaning process

KPI insights

Visualizations and interpretation

Python and Power BI steps in simple language

These documents are written from a beginner-friendly perspective but still show professional analytical thinking.

💡 Business Insights (Summary)

Some key takeaways from the project:

Discounts alone do not guarantee better ratings.

Average price and discount levels can guide positioning and profitability decisions.

Understanding which categories respond well to discounts can help optimize campaigns.

Tracking discount trends over time helps monitor promotional strategy and its consistency.

🙋‍♀️ About Me

I am Rishika Jaiswal, a transitioning professional from a non-IT background into the Data Analytics field.
Through this internship, I worked on:

Real-world data

Practical Python analysis

Dashboards in Power BI

Writing structured analytical reports

I am actively looking for opportunities as a Junior Data Analyst / Data Analyst Intern.

📬 Contact

Email: rishikajaiswal2030@gmail.com

Feel free to explore the repository and share any feedback or suggestions!
