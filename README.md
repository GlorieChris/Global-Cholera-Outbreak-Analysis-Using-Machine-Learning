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
- The dataset includes yearly records of cholera outbreaks from multiple countries, with features such as:

  - Country: The name of the country where cholera cases were reported. This helps in identifying geographic trends and regional hotspots for cholera outbreaks.

  - WHO Region: The World Health Organization regional grouping for each country (e.g., Eastern Mediterranean, Africa, South-East Asia). Useful for regional aggregation and comparative analysis.

  - Year: The calendar year in which the cholera cases and deaths were reported. Useful for analyzing time-based trends, spikes, or reductions in cholera outbreaks.

  - Number of reported cases of cholera (Target Variable): Total number of cholera cases officially reported in that country for the given year. This is the target variable used for prediction.

  - Number of reported deaths from cholera: The Total number of deaths caused by cholera in that country during the specified year. It provides insight into the severity and impact of outbreaks.

  - Cholera case fatality rate: The percentage of reported cholera cases that resulted in death. Calculated as (deaths / cases) * 100. It helps assess how deadly the outbreaks are in different regions or years.

## 🔑 Key Steps

1. Data Loading and Cleaning
- Loaded the global cholera dataset

- Removed null values and columns with insufficient data

- Verified and corrected data types (e.g., years, numeric columns)

- Renamed columns for consistency and ease of use

2. Exploratory Data Analysis (EDA)
- Identified Top 50 countries with the highest number of reported cholera cases

- Analyzed cholera case trends year by year

- Compared regions (WHO-defined) to see burden of outbreaks

- Calculated Case Fatality Rates (CFR) for different countries and years

- Used bar plots for visual representation

3. Geospatial Visualization
- Created a world map (choropleth) of cholera cases using matplotlyb

- Mapped cases by country using ISO codes and interactive visuals

4. Feature Engineering
- Encoded categorical features like Country and WHO Region

- Selected Year, Encoded Country, Encoded Region as features

- Used Number of Reported Cases as the target variable

## 🤖 Models Used
Trained and tested the following regression models:

- Linear Regression

- Decision Tree Regressor

- Random Forest Regressor

## 🧪 Model Evaluation
Measured model performance using:

- R² Score

- Mean Squared Error (MSE)

- Root Mean Squared Error (RMSE)

Random Forest Regressor gave the best performance

## 📈 Key Insights 
🔝 Cholera cases are heavily concentrated in a few countries, with the Top 10 countries accounting for a major share of global reported cases between 2000–2016.

🌍 India, Haiti, Peru, and African countries dominate the top 50, with nations like the Democratic Republic of Congo, Mozambique, and Tanzania consistently reporting high numbers.

📉 Some countries show declining trends, while others have irregular spikes, suggesting outbreaks are often linked to local conditions like conflict, flooding, or water crisis.

📆 Yearly trends reveal that cholera cases do not consistently rise or fall globally, indicating regional variations and different levels of health infrastructure.

📊 The Case Fatality Rate (CFR) is relatively low in most countries. Still, spikes in a few, like Italy, Bangladesh, and Oman show where cholera is more deadly, possibly due to delayed response or healthcare access issues.

🧭 WHO Region-wise analysis shows:

- Africa and the Eastern Mediterranean consistently carry the heaviest burden.

- South-East Asia and Europe show a decline in trend over the years

- Americas and Western Pacific report little, static to no activity, highlighting regional inequalities.

- 🗺️ The world map visualization clearly shows Countries clustering of outbreaks.

- 🤖 Random Forest Regressor outperformed other models, showing it captured the nonlinear relationships in cholera case prediction better than Linear or Decision Tree models.

⚙️ Tools & Technologies
- Python

- Pandas, NumPy

- Matplotlib, Seaborn, Plotly

- Scikit-learn

- GeoPandas, PyCountry

- Jupyter Notebook

💡 Future Improvements
- Incorporate climate data (e.g., rainfall, temperature)

- Add socioeconomic indicators like access to water, sanitation, and population density

- Deploy the model using Streamlit or Flask for real-time predictions

- Use time-series models like ARIMA or LSTM for forecasting outbreaks
