---
title: Coworking Space
author: Gabriel
description: Data Projects
date: 2025-01-30 22:30:00 +0200
categories: [Projects, Coworking Space]
tags: [Projects]
pin: true
math: true
mermaid: true
---
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0D76A8)](https://www.linkedin.com/in/braydon-coyer/)

[![GitHub FilmAffinity Repository](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GabrielFersPin/Coworking.git)

<a href="https://github.com/GabrielFersPin/Coworking.git" target="_blank">
    <img align="center" src="https://www.freepik.com/free-vector/coworking-space-illustration-with-people-working-together_12150865.htm?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2" alt="Coworking Space" height="100" />
</a>

🏢 Coworking Space Analysis & Recommendation System
📌 Project Overview
This project analyzes coworking spaces across major cities (Barcelona, Madrid, New York, and Tokyo) to provide insights and build a recommendation system based on pricing, location, and user ratings. The goal is to help professionals and businesses find the best coworking space based on their preferences.

🚀 Features
Web Scraping: Extracted coworking space data from Google Maps and other sources.
Data Analysis: Cleaned and processed data, including population, income, transportation, and ratings.
Machine Learning:
Price Prediction: Implemented Ridge Regression and Random Forest models to predict day pass prices.
Recommendation System: Uses a scoring mechanism considering price, rating, and distance from the city center.
Interactive Visualization:
Power BI Dashboards: Insights on coworking spaces, transportation, and pricing.
Folium Map: Visual representation of coworking locations with user ratings.
Streamlit Web App: A user-friendly interface to explore coworking options dynamically.
📊 Data Sources
Google Maps API: Extracted locations, ratings, and user reviews.
Wikipedia & Census Data: Incorporated neighborhood population and income statistics.
Manual Data Collection: Pricing details for the top-rated coworking spaces.
🔍 Data Processing
Added distance from city center as a key metric.
Computed weighted rating scores to account for both rating and user count.
Feature engineering for predictive modeling.
🤖 Machine Learning Models
1️⃣ Ridge Regression
Best Parameters: alpha=10.0
MAE: 3.58 (Mean Absolute Error)
2️⃣ Random Forest Regressor
Best Parameters: max_depth=None, n_estimators=100
MAE: 15.93, RMSE: 21.67
🔮 Recommendation System
A scoring function ranks coworking spaces by:

Affordability: (User's max price - Predicted Price)
Quality: Rating × 10
Convenience: Distance from the city center (penalized)
🌎 Interactive Map Example
🛠 Technologies Used
Python: pandas, scikit-learn, folium, Streamlit
Machine Learning: Regression models for price prediction
Visualization: Power BI, Folium, Streamlit
💡 How to Use
Clone the repository:
git clone https://github.com/GabrielFersPin/Coworking.git
cd Coworking
Create a Virtual Environment:
python -m venv new_venv
``
Activate the Virtual Environment:
Windows:
new_venv\Scripts\activate
MacOS/Linux:
source new_venv/bin/activate
Install Dependecies:
pip install -r requirements.txt
Run the Streamlit app:
streamlit run app.py
🏆 Acknowledgments
Special thanks to the open-source community and data providers for enabling this analysis.

📌 Author: Gabriel Fernandes Pinheiro
🔗 LinkedIn | GitHub

[[GitHub Coworking Repository](https://github.com/GabrielFersPin/Coworking.git)]
