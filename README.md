# Oil-and-Gas-Project-
<div align="center">

  <img src="https://miro.medium.com/v2/resize:fit:1400/1*mkSvMkBzX9oQfnB9-w-45w.png" alt="Oil Rig" width="400">

  <h1>Oil and Gas Production Analysis </h1>

  <p>
    Analyzing well production data to uncover key insights and predict future performance.
  </p>

  <a href="https://github.com/saikat912/Oil-and-Gas-Project-">
    <img src="https://img.shields.io/github/stars/your-username/Oil-Gas-Project-?style=social" alt="Stars Badge"/>
  </a>
  <a href="https://github.com/saikat912/oil-Gas-Project/network/members">
    <img src="https://img.shields.io/github/forks/saikat912/Oil-and-Gas-Project-?style=social" alt="Forks Badge"/>
  </a>
  <a href="https://github.com/saikat912/Oil-and-Gas-Project-/pulls">
    <img src="https://img.shields.io/github/issues/saikat912/Oil-and-Gas-Project-" alt="Pull Requests Badge"/>
  </a>
  <a href="https://github.com/saikat912/Oil-and-Gas-Project-/issues">
    <img src="https://img.shields.io/github/issues-closed/saikat912/Oil-and-Gas-Project-" alt="Issues Closed Badge"/>
  </a>

</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#overview">Overview</a></li>
    <li><a href="#key-features">Key Features</a></li>
    <li><a href="#technologies-used">Technologies Used</a></li>
    <li><a href="#data-description">Data Description</a></li>
    <li><a href="#exploratory-data-analysis">Exploratory Data Analysis</a></li>
    <li><a href="#feature-engineering">Feature Engineering</a></li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

## Overview
This project performs an in-depth analysis of oil and gas well production data to identify critical factors that influence production rates. The analysis includes:
- Comprehensive data cleaning to ensure data quality.
- Exploratory Data Analysis (EDA) to visualize trends and relationships.
- Feature engineering to create new, insightful variables.
- Model building to predict well production rates.

## Key Features
- **Data Cleaning:** Comprehensive handling of missing values and data type conversions.
- **Exploratory Data Analysis (EDA):** Detailed visualizations and statistical analysis using Seaborn and Matplotlib.
- **Feature Engineering:** Creation of 'Age' and 'ProductionPerDepth' to better model production.
- **Multicollinearity Check:** VIF analysis to ensure model stability and reliability.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

<p align="center">
  <img src="https://forthebadge.com/images/badges/made-with-python.svg" alt="Made with Python">
</p>

## Data Description
The dataset contains information about oil and gas wells, including:
- `WellID`: Unique identifier for each well.
- `Depth`: Well depth.
- `YearDrilled`: Year the well was drilled.
- `WellType`: Type of well (e.g., Offshore, Onshore).
- `Geology`: Geological formation (e.g., Sandstone, Shale).
- `Production`: Production volume.
- `Age`: Age of the well.
- `ProductionPerDepth`: Production volume per depth.

## Exploratory Data Analysis
A detailed EDA was conducted to understand the relationships between different features and production rates. Key steps included:
- Summary statistics for numerical features.
- Visualizations of feature distributions and correlations.
- Identification of outliers and data anomalies.

<details>
  <summary>Click to view EDA examples</summary>
  <img src="url_to_your_eda_visualization_1" alt="EDA Visualization 1" width="400">
  <img src="url_to_your_eda_visualization_2" alt="EDA Visualization 2" width="400">
</details>

## Feature Engineering
New features were engineered to enhance the predictive power of the models:
- **Age:** Calculated as the difference between the current year and the `YearDrilled`.
- **ProductionPerDepth:** Calculated as `Production` divided by `Depth`, providing a normalized production rate.

## Getting Started

### Prerequisites
- Python 3.6+
- Jupyter Notebook
- Required Python packages:
- 
