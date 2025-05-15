# 🌍 Global-Cholera-Outbreak-Analysis-Using-Machine-Learning
Visualizing and predicting global cholera outbreaks using machine learning to support global health monitoring and decision-making

## 📌 Project Overview
This project analyzes global cholera outbreak data to uncover patterns in the number of reported cases across different countries and years. Beyond visual analysis, machine learning models are applied to predict the number of cholera cases based on features such as year, region, and country. The aim is to support data-driven decisions for international health policy, outbreak prediction, and targeted interventions.

## 🧾 Problem Statement
Cholera continues to be a major global health concern, particularly in developing countries with limited access to clean water and sanitation. Understanding the dynamics of cholera outbreaks—where and when they occur—is vital to preventing future outbreaks and saving lives.

This project uses global cholera surveillance data to:

- Visualize the spread and burden of cholera cases by year and country

- Identify high-risk countries and regions

- Apply machine learning techniques to predict reported cholera cases and uncover driving factors

By focusing on the number of reported cholera cases as the target variable, the analysis provides insights into patterns that can inform global health planning.

## 📊 Dataset Description
The dataset includes yearly records of cholera outbreaks from multiple countries, with features such as:

- Country: The name of the country where cholera cases were reported. This helps in identifying geographic trends and regional hotspots for cholera outbreaks.

- WHO Region: The World Health Organization regional grouping for each country (e.g., Eastern Mediterranean, Africa, South-East Asia). Useful for regional aggregation and comparative analysis.

- Year: The calendar year in which the cholera cases and deaths were reported. Useful for analyzing time-based trends, spikes, or reductions in cholera outbreaks.

- Number of reported cases of cholera (Target Variable): Total number of cholera cases officially reported in that country for the given year. This is the target variable used for prediction.

- Number of reported deaths from cholera: The Total number of deaths caused by cholera in that country during the specified year. It provides insight into the severity and impact of outbreaks.

- Cholera case fatality rate: The percentage of reported cholera cases that resulted in death. Calculated as (deaths / cases) * 100. It helps assess how deadly the outbreaks are in different regions or years.

🔑 Key Steps
Data Cleaning

Removed null values and irrelevant columns

Converted year and case-related data to appropriate formats

Normalized country and region labels

Exploratory Data Analysis (EDA)

Top 10 countries with highest cholera cases

Year-by-year trend of outbreaks globally

Regional breakdown using bar and pie charts

Case Fatality Rate computation

Geospatial Visualization

Choropleth world map to show distribution of cholera cases globally

Machine Learning Modeling

Feature selection: Country (encoded), WHO Region (encoded), Year

Target variable: Reported cholera cases
