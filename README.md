 Global GDP & Internet Usage Analysis (UN Data)

 Project Overview

This project explores the relationship between economic growth and digital access using real-world datasets from the United Nations.
Using Python and Pandas, I analyzed GDP per capita and internet usage trends across countries from 1990 to 2020, transforming raw CSV files into meaningful insights through data cleaning, exploratory analysis, and visualization.

This project was completed during Week 8 at Nashville Software School as my first hands-on Python data analysis project.

🛠 Tools & Technologies

Python

Pandas

NumPy

Data Visualization

Matplotlib

Seaborn

Environment

Jupyter Notebook

Techniques

Data cleaning & preprocessing

Exploratory Data Analysis (EDA)

Data merging & reshaping

Quantile-based grouping (qcut)

Statistical interpretation & storytelling

 Datasets

GDP per Capita (UN World Development Indicators)

Internet Users Percentage (UN / ITU)

Raw CSV files contained metadata rows, footnotes, and inconsistent formatting, requiring custom handling during ingestion.

🔍 Key Analysis & Visualizations
📈 GDP Per Capita Analysis

Examined global GDP per capita distributions using:

Histograms

Density plots

Boxplots

Violin plots

Compared GDP per capita across 1990, 2000, 2010, and 2020

Identified:

The first country to exceed $100,000 GDP per capita

Countries with the highest and lowest GDP per capita in 2020

Long-term GDP trends for these countries

🌐 Internet Usage Analysis

Analyzed the growth of internet adoption over time

Identified the first year with non-zero internet usage values

Compared distributions of internet usage in 2000 vs 2014

Measured digital inequality across countries

🔗 Combined Insights

Merged GDP and internet usage datasets while preserving all observations

Used FacetGrid visualizations to compare GDP trends for countries with the highest internet adoption

Created a GDP group classification (Low, Medium, High) using quantiles

Compared median internet usage across GDP groups

💡 Key Insights

GDP per capita has increased globally over time, but growth remains highly uneven

Higher internet adoption is strongly correlated with higher GDP per capita

Several countries had lower GDP per capita in 2020 than in 1990, challenging assumptions of universal economic progress

Infrastructure, policy, and regional factors play a critical role in economic and digital development


🎯 Skills Demonstrated

Working with messy, real-world datasets

Diagnosing and resolving data ingestion errors

Selecting appropriate visualizations for different analytical questions

Communicating insights through clear, data-driven narratives
