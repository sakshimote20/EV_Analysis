# EV_Analysis
## Project Overview

This project focuses on analyzing the adoption of Electric Vehicles (EVs) across different states and assessing the availability of charging stations. The goal is to uncover trends, disparities, and relationships between EV adoption and charging infrastructure using Exploratory Data Analysis (EDA).

## Dataset Description

+ The dataset contains state-wise data on:

+ EV Registrations: Includes counts of Two-Wheelers, Three-Wheelers, Four-Wheelers, Goods Vehicles, and Public Service Vehicles.

+ Charging Infrastructure: Total number of charging stations available in each state.

+ Grand Total: Sum of all vehicle types for each state.

## Project Objectives

+ Identify trends in EV adoption across different states.

+ Analyze the correlation between EV registrations and charging station availability.

+ Highlight disparities in charging infrastructure across states.

+ Provide insights for policymakers and stakeholders to improve EV adoption.

## EDA Steps and Key Insights

### 1. Distribution of Different Vehicle Types

+ Box plots reveal that Two-Wheelers and Three-Wheelers dominate EV adoption in most states.

+ Higher variation is observed in Four-Wheelers and Public Service Vehicles across states.

### 2. Relationship Between EVs and Charging Stations

+ Scatter plots show a general positive correlation between the total number of EVs and available charging stations.

+ Some states have high EV adoption but lack adequate charging infrastructure, indicating a gap.

### 3. Correlation Analysis

+ A correlation heatmap highlights strong relationships between different vehicle categories.

+ Charging stations show a moderate correlation with total EVs, meaning other factors may influence infrastructure growth.

### 4. Top 5 States with Highest EV Adoption

+ Bar charts identify states with the highest total EV registrations.

+ These states need well-planned charging networks to support growing demand.

### 5. Top 5 States with Most Charging Stations

+ The states leading in charging infrastructure do not always align with those leading in EV adoption.

+ This suggests policy interventions are needed to balance infrastructure with demand.

## Requirements

To run the analysis, ensure you have the following Python libraries installed:

pip install pandas numpy matplotlib seaborn

## Usage

+ Load the dataset in a Pandas DataFrame.

+ Run the Python script for EDA.

+ Visualize trends using the generated plots.

+ Interpret key findings for decision-making.

## Conclusion & Recommendations

+ Infrastructure Gaps: Some states with high EV adoption lack sufficient charging stations.

+ Development Disparities: Charging stations are not evenly distributed across states.

+ Policy Recommendations: Governments should strategically expand charging networks based on EV adoption trends.

+ Future Work: More granular data (e.g., urban vs. rural breakdown) would improve insights.
