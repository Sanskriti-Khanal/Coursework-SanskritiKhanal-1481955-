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

| District     | County           | 🏠 House | ⚡ Broadband | 🎓 School | 🚓 Crime | ⭐ Total Score |
|--------------|------------------|----------|--------------|-----------|----------|----------------|
| Rotherham    | South Yorkshire  | **10**   | **10**       | 0         | 10       | **7.5**         |
| Bradford     | West Yorkshire   | **10**   | 0            | **10**    | 7.05     | **6.76**        |
| Doncaster    | South Yorkshire  | 7.86     | 2.38         | 6.22      | 7.73     | **6.05**        |
| Barnsley     | South Yorkshire  | 9.41     | 6.62         | 1.24      | 6.84     | **5.78**        |
| Leeds        | West Yorkshire   | 0        | **10**       | 3.10      | **10**   | **5.78**        |
| Sheffield    | South Yorkshire  | 0        | 0            | **10**    | 0        | **2.5**         |

> 📌 *Scores are out of 10 per metric. Final score is the average of the four.*

## 📁 Folder Structure

