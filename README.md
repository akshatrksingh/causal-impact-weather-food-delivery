# Causal Impact of Weather on Food Delivery Times

### Project Overview
This project, conducted as part of the **CS-GY 6053: Foundations of Data Science** course at **New York University (NYU)** (Fall 2024), explores the **causal impact of weather** conditions on **food delivery times**. In food delivery logistics, customer satisfaction heavily depends on timely delivery, which is influenced by external factors like weather and traffic. Poor weather conditions can directly slow down delivery times due to reduced visibility and hazardous road conditions. Simultaneously, adverse weather can increase traffic congestion, which indirectly delays deliveries.

### Problem Statement

The primary research question driving this study is: **How do weather conditions causally influence food delivery times, with traffic density acting as a confounding factor in this relationship?** By addressing this question, the analysis aims to uncover actionable insights to optimize delivery operations under diverse external scenarios like weather and traffic density.

### Data Description

The dataset used in this project is sourced from Kaggle and focuses on delivery times under varying external conditions. The 100 data points were selected to ensure diversity across weather and traffic conditions, providing sufficient variation for causal inference. The dataset includes key variables such as:

- **Delivery Time (`time`)**: The time taken for a delivery, measured in minutes, serving as the primary **outcome variable** in the causal model.
- **Weather Conditions (`weather`)**: Categorical descriptions of weather, treated as the **treatment variable** in the causal model. The categories include:
  - Cloudy
  - Fog
  - Sandstorms
  - Stormy
  - Sunny
  - Windy
- **Traffic Density (`traffic`)**: The level of traffic at the time of delivery, which acts as a **potential confounder** in the causal relationship between weather and delivery time. The categories include:
  - High
  - Low
  - Medium

### Key Steps and Methodology

#### 1. **Causal Model**
- Defined the assumed causal relationships between **weather**, **traffic density** and **delivery times** with the help of a Directed Acyclic Graph.

#### 2. **Statistical Models** and **Posterior Models**
- Performed prior predictive checks, validated statistical models on simulated data, built posterior models on observed data, and conducted posterior diagnostics and posterior predictive checks.

### Files and Folders
- **data/**: Contains the processed dataset.
- **notebooks/**: Contains the Jupyter notebook used for analysis.
