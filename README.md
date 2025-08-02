# 🏡 Yorkshire Residential Recommendation System

This project builds a data-driven **district recommendation system** for **South and West Yorkshire**, UK. It integrates real-world datasets—covering **house prices, broadband speeds, crime rates, and school performance**—to help users make informed decisions when choosing places to live.

## 📌 Project Overview

Using the **Data Mining Lifecycle**, the project progresses through:
- Data Acquisition
- Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Linear Modelling
- Scoring & Recommendation

Each district receives a score (0–10) per factor, combined into an overall recommendation score. The top districts are visualized and ranked based on these results.

## 🔍 Key Datasets

- 🏠 **House Prices** (UK Price Paid Data)
- ⚡ **Broadband Speeds** (Ofcom)
- 🚓 **Crime Rates** (UK Police Data)
- 🎓 **School Attainment (Attainment 8)** (Department for Education)
- 👥 **Population Data** (ONS)

All datasets are sourced from **public government repositories** and processed using **R** and the `tidyverse` ecosystem.

## 📊 Final Recommendation Scores

| County          | Town         | HousePrice_Score | Broadband_Score | School_Score | Crime_Score | Total_Score |
|-----------------|--------------|------------------|------------------|--------------|-------------|-------------|
| South Yorkshire | Not Known    | 9.94             | 8.25             | 10.00        | 9.99        | 9.54        |
| West Yorkshire  | Wetherby     | 9.94             | 8.25             | 10.00        | 9.99        | 9.54        |
| South Yorkshire | Sheffield    | 9.94             | 8.25             | 8.37         | 9.99        | 9.14        |
| South Yorkshire | Mexborough   | 9.94             | 8.25             | 7.55         | 9.99        | 8.93        |
| South Yorkshire | Doncaster    | 9.94             | 8.25             | 7.14         | 9.99        | 8.83        |
| South Yorkshire | Whiston      | 9.94             | 10.00            | 4.97         | 9.99        | 8.72        |
| South Yorkshire | Rawmarsh     | 9.94             | 9.97             | 4.97         | 9.99        | 8.72        |
| West Yorkshire  | Bramley      | 9.94             | 10.00            | 4.97         | 9.99        | 8.72        |
| South Yorkshire | Worsbrough   | 9.94             | 9.51             | 4.97         | 9.99        | 8.60        |
| South Yorkshire | Thorne       | 9.94             | 9.20             | 4.97         | 9.99        | 8.52        |
|-----------------------------------------------------------------------------------------------------------------|

