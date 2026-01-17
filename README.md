🦠 COVID-19 Data Analysis Project Using Python

A comprehensive data analysis project performed on the COVID-19 dataset using Python, Pandas, NumPy, Matplotlib, and Seaborn.
The goal of this project is to explore, clean, analyze, visualize, and extract meaningful insights from real-world COVID-19 data.

🔗 Dataset Source
https://raw.githubusercontent.com/SR1608/Datasets/main/covid-data.csv

🎯 Project Objectives

✔ Load and explore dataset
✔ Perform high-level & low-level data understanding
✔ Clean and preprocess data
✔ Handle missing values & duplicates
✔ Convert and engineer date columns
✔ Perform aggregation using groupby
✔ Create new features
✔ Visualize metrics and insight patterns
✔ Export final processed output

🧩 Technologies & Libraries Used

Python 3.x

Pandas

NumPy

Seaborn

Matplotlib

🧱 Steps Performed in the Project
1️⃣ Data Loading

Dataset imported from GitHub using pandas

2️⃣ High Level EDA

Shape (rows & columns)

Data types

Info & describe summary

3️⃣ Low Level EDA

Includes:

unique value counts

statistical measures

quartiles

min/max

continent-wise HDI & GDP insights

4️⃣ Filtering & Feature Selection

Selected essential columns:

['continent', 'location', 'date', 'total_cases', 'total_deaths',
 'gdp_per_capita', 'human_development_index']

5️⃣ Data Cleaning

Remove duplicates

Handle missing values

Drop missing continents

Fill remaining NaN with 0

6️⃣ Date Handling

Convert to datetime format

Extract month from date

7️⃣ Data Aggregation

Grouped by continent

Aggregated using max()

Stored results in df_groupby

8️⃣ Feature Engineering

Created new feature:

total_deaths_to_total_cases = total_deaths / total_cases

9️⃣ Data Visualization

Performed:

Histogram (Univariate)

Scatter Plot

Pair Plot

Bar Chart

with enhanced styling using Seaborn.
