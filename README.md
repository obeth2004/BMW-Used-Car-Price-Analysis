BMW Used Car Market Analysis
This project analyzes a dataset of over 10,000 BMW used car listings to uncover pricing patterns, model-specific demand, and the key factors influencing resale value. The goal is to provide actionable insights for both dealerships and buyers to make data-driven decisions.

Project Overview
The analysis focuses on identifying how various vehicle attributes—such as mileage, fuel type, and engine size—impact the market price of BMW vehicles.

Dataset Features
The dataset contains 10,781 records with 9 key features:

model: The specific BMW series or model (e.g., 5 Series, 3 Series, X3).

year: Registration year (ranging from 1996 to 2020).

price: The listing price in GBP.

transmission: Manual, Automatic, or Semi-Auto.

mileage: Total miles driven.

fuelType: Diesel, Petrol, Hybrid, Electric, or Other.

tax: Road tax cost.

mpg: Fuel efficiency (miles per gallon).

engineSize: Engine capacity in liters.

Key Workflow
Data Cleaning: Stripping white spaces from column names and model strings to ensure consistent categorization.

Exploratory Data Analysis (EDA): Using Matplotlib, Seaborn, and Plotly to visualize price distributions and correlations.

Advanced Visualization: Leveraging Bokeh for interactive plots to explore complex relationships between features like mileage and price.

Feature Engineering: Preparing data for analysis using StandardScaler and LabelEncoder from Scikit-learn.

Installation & Requirements
To run this notebook, you will need the following Python libraries:

Bash
pip install pandas numpy matplotlib seaborn plotly scikit-learn bokeh
