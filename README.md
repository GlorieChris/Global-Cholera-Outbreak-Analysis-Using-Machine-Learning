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

📊 Dataset Description
The dataset includes yearly records of cholera outbreaks from multiple countries, with features such as:

Country: Nation where cholera cases were reported

WHO Region: Associated WHO regional group

Year: Year of the report

Number of Reported Cases (Target Variable)

Deaths (optional in some rows)

The data spans multiple continents and regions, enabling a global-scale analysis.

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
