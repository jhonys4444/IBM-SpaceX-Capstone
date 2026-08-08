# IBM SpaceX Falcon 9 Landing Prediction Capstone

This repository contains my completed work for the IBM Data Science Capstone Project, where I analyzed SpaceX Falcon 9 launch data to explore the factors associated with successful first-stage booster landings and to build predictive classification models.

The project covers the complete data science workflow, from data collection and preprocessing to exploratory data analysis, interactive visualization, dashboard development, and machine learning.

## Project Objectives
- Collect SpaceX launch data from the SpaceX REST API
- Extract additional launch information through web scraping (Wikipedia)
- Perform data wrangling and feature engineering
- Explore launch patterns using SQL, Python, and data visualization
- Build interactive dashboards with Plotly Dash
- Create interactive geographic maps with Folium
- Train and compare multiple classification models to predict landing success

## Estructura del Proyecto

\```
IBM-SpaceX-Capstone/
├── notebooks/
│   ├── 01_API_Data_Collection.ipynb
│   ├── 02_Web_Scraping.ipynb
│   ├── 03_Data_Wrangling.ipynb
│   ├── 04_EDA_SQL.ipynb
│   ├── 05_EDA_Visualization.ipynb
│   ├── 06_Folium_Map.ipynb
│   ├── 07_Dash_Dashboard.ipynb
│   └── 08_Machine_Learning.ipynb
├── dash_app/
│   └── spacex-dash-app.py
├── data/
├── screenshots/
├── README.md
└── requirements.txt
\```

## Technologies Used
- Python
- Pandas
- NumPy
-Matplotlib
- Seaborn
- SQL (SQLite)
- BeautifulSoup
- Folium
- Plotly & Dash
- Scikit-learn

## Machine Learning Models
The following classification algorithms were trained and evaluated using GridSearchCV and cross-validation:

- Logistic Regression
- Support Vector Machine (SVM)
- Decision Tree
- K-Nearest Neighbors (KNN)

Among the evaluated models, the Decision Tree classifier achieved the highest cross-validation accuracy in this project.

## Key Insights
- Launch success rates improved significantly over time.
- Launch site and orbit type were associated with landing outcomes.
- Payload mass showed a relationship with mission success in specific ranges.
- Interactive dashboards and geographic maps provided additional operational insights into launch locations and booster recovery patterns.

## Dashboard Preview

The project includes a Plotly Dash application that allows users to:

- Filter launches by launch site
- Explore payload ranges
- Compare success and failure outcomes
- Visualize booster version performance interactively

## Project Context

This project was completed as part of the IBM Data Science Professional Certificate – Applied Data Science Capstone and serves as a portfolio project demonstrating practical skills in:

- Data acquisition
- Data cleaning
- SQL analysis
- Exploratory data analysis
- Interactive visualization
- Machine learning
- Technical reporting

## Author

Jhonathan Camilo Baracaldo

Data Analytics | Business Intelligence | Data Scienct | Financial Analytics (soon)
