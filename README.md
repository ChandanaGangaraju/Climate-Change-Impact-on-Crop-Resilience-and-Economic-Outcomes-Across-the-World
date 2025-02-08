# Climate-Change-Impact-on-Crop-Resilience-and-Economic-Outcomes-Across-the-World

## Overview
This project investigates the impact of climate change on agricultural productivity, crop resilience, and economic outcomes globally. Using regression and machine learning models, we analyze how temperature, CO2 emissions, precipitation, and extreme weather events influence crop yield and soil health. The study also evaluates adaptation strategies, such as crop rotation and water management, to enhance resilience against climate change.

## Problem Statement
Climate change is disrupting agricultural productivity by altering temperature patterns, increasing CO2 emissions, and affecting precipitation levels. These changes significantly impact soil health, crop yields, and the economic stability of farming regions. Our study aims to:
- Understand the influence of climate variables on agriculture.
- Identify sustainable adaptation strategies to mitigate climate impacts.
- Provide data-driven insights for policymakers and farmers.

## Motivation
With the increasing frequency of extreme weather events, farmers and agricultural stakeholders need predictive models to make informed decisions. This project explores key climate-agriculture relationships, highlighting the importance of sustainable farming practices in mitigating the effects of climate change.

## Dataset
We used a dataset from **Kaggle**, containing:
- **10,000 entries** from **1990-2024** across **15 variables**.
- Key features: **Crop Type, Yield (MT/HA), Temperature (°C), Precipitation (mm), CO2 Emissions (MT), Soil Health Index, and Extreme Weather Events.**
- The dataset is **clean** with no missing values, ensuring robust analysis.

## Methodology
Our approach involves:
1. **Data Preprocessing:** Cleaning and normalizing data.
2. **Exploratory Data Analysis (EDA):** Identifying patterns and relationships between climate factors and crop yield.
3. **Statistical Modeling:** Using **OLS Regression and Random Forest** to analyze key predictors.
4. **Machine Learning Models:** Applying predictive models to forecast crop productivity under changing climate conditions.
5. **Results Interpretation:** Evaluating how adaptation strategies impact yield and economic stability.

## Key Findings
- **Temperature increases** moderately benefit colder regions but harm crop yields in warmer climates.
- **CO2 emissions negatively affect** crop productivity, likely due to extreme weather impacts.
- **Precipitation patterns matter**: Too little or too much rainfall reduces crop yield.
- **Effective adaptation strategies** (crop rotation, drought-resistant crops, and water management) significantly improve soil health and yield.
- **Random Forest Model** identified **Temperature, CO2 Emissions, and Precipitation** as the top predictors of agricultural outcomes.

## Installation
1. Clone the repository:
    ```sh
    git clone https://github.com/ChandanaGangaraju/Climate-Change-Impact-on-Crop-Resilience-and-Economic-Outcomes-Across-the-World.git
    ```
2. Navigate to the project directory:
    ```sh
    cd Climate-Change-Impact-on-Crop-Resilience-and-Economic-Outcomes-Across-the-World
    ```
3. (Optional) Create and activate a virtual environment:
    ```sh
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```
4. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
