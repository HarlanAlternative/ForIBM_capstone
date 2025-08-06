# SpaceX Data Science Capstone Project

## Overview
This project analyzes SpaceX launch data to predict the success rate of Falcon 9 first stage landings using machine learning techniques.

## Project Components

### Data Collection
- **API Data Collection**: Collects SpaceX launch data from the SpaceX API
- **Web Scraping**: Extracts Falcon 9 launch records from Wikipedia

### Data Analysis
- **Data Wrangling**: Cleans and prepares the dataset for analysis
- **SQL Analysis**: Performs database queries to extract insights
- **Data Visualization**: Creates charts and graphs to visualize launch patterns
- **Geographic Analysis**: Analyzes launch site locations and their impact on success rates

### Machine Learning
- **Prediction Model**: Trains classification models to predict landing success
- **Model Evaluation**: Compares different algorithms (Decision Tree, SVM, KNN, Logistic Regression)

### Interactive Dashboard
- **Plotly Dash App**: Real-time dashboard for launch data visualization
- **Interactive Features**: Filter by launch site, date range, and mission outcomes

## Files Included

### Jupyter Notebooks
- `jupyter-labs-spacex-data-collection-api-v2.ipynb` - API data collection
- `jupyter-labs-webscraping (1).ipynb` - Web scraping from Wikipedia
- `labs-jupyter-spacex-Data wrangling-v2.ipynb` - Data cleaning and preparation
- `jupyter-labs-eda-sql-coursera_sqllite.ipynb` - SQL database analysis
- `jupyter-labs-eda-dataviz-v2.ipynb` - Data visualization and EDA
- `lab-jupyter-launch-site-location-v2.ipynb` - Geographic analysis
- `SpaceX-Machine-Learning-Prediction-Part-5-v1.ipynb` - Machine learning models

### Data Files
- `dataset_part_1.csv` - Main dataset
- `spacex_launch_geo.csv` - Geographic data
- `spacex_launch_dash.csv` - Dashboard data
- `my_data1.db` - SQLite database

### Applications
- `spacex_dash_app.py` - Interactive dashboard application

## Key Findings
- Decision Tree achieved highest accuracy (87.3%) for landing prediction
- Launch site location significantly impacts landing success rates
- Payload mass and orbit type influence landing outcomes
- Interactive dashboard enables real-time launch analysis

## Technologies Used
- Python
- Jupyter Notebooks
- Pandas, NumPy, Matplotlib, Seaborn
- Plotly Dash
- Scikit-learn
- SQLite
- BeautifulSoup (Web Scraping)
- Requests (API calls)

## Setup Instructions
1. Install required Python packages
2. Run Jupyter notebooks in order
3. Launch dashboard with `python spacex_dash_app.py` 