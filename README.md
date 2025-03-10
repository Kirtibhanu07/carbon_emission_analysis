# Analysing the Impact of Carbon Emmission on Global Temperature

This project explores the relationship between CO₂ concentrations and global temperature changes, using statistical analysis, predictive modeling, and machine learning techniques. The goal is to assess historical trends, simulate "What-If" climate scenarios, and predict future temperature changes based on CO₂ levels.

## Key Features
- CO₂ vs Temperature Correlation Analysis
- Time-Series Trends of CO₂ & Global Warming
- Statistical Testing (Pearson, Spearman, Granger Causality)
- K-Means Clustering to Identify Climate Patterns
- Predictive Modeling (Linear Regression)
- "What-If" CO₂ Scenario Simulations
- Interactive Visualizations with Plotly

## Approach & Methodology

**Data Collection & Preprocessing**
- Data includes historical CO₂ levels (ppm) and temperature anomalies (°C).
- Cleaned, standardized, and structured for statistical & ML analysis

**Statistical Analysis & Hypothesis Testing**
- Pearson & Spearman Correlation → Strong positive correlation (0.95+).
- Granger Causality Test → Weak short-term causality but strong long-term relationship.

## Data Visualizations

### - **Temperature Changes Over the Years**
![Temperature Change](https://github.com/user-attachments/assets/707223d4-2e33-4c29-9627-30d59aa8ba47)

### - **Temperature vs CO₂ Concentration**
![Temp change vs co2](https://github.com/user-attachments/assets/7076c8ef-1107-4972-98ab-971ca897e6a7)

### - **Seasonal CO₂ Trend**
![Seasonal trend vs co2](https://github.com/user-attachments/assets/23bc6857-d75a-4e3a-b222-4cb21c3e8fc3)

### - **Clustering Climate Pattern**
![climate pattern](https://github.com/user-attachments/assets/8982ae4f-e713-43cf-8c1c-4ea2eee1f4cf)

## Predictive Modeling: "What-If" Scenarios
- Trained a Linear Regression Model to simulate the impact of CO₂ concentration changes.

#### Predicted temperature changes for different CO₂ emission scenarios:
- Increase CO₂ by 10% → Higher temp
- Decrease CO₂ by 10% → Potential cooling
- Increase CO₂ by 20% → Significant warming
- Decrease CO₂ by 20% → More cooling

### - Changes in Temperature Under Different CO₂ Scenarios
![Simulated Temperature Change Under Different CO₂ Scenarios](https://github.com/user-attachments/assets/0c28a90d-5ba7-4db0-a51d-5764a4cd22b2)

## Results & Findings
- CO₂ concentration is highly correlated with temperature anomalies (r = 0.9554).
- Model predicts ~0.015°C increase per ppm of CO₂ rise.
- Reducing CO₂ emissions can slow down global warming.
- K-Means clustering effectively identifies climate patterns over time.

### Contact & Acknowledgments
- 👤 Author: Kirti Bhanu
- 🌐 LinkedIn: https://www.linkedin.com/in/kirtibhanu07
- 📧 Email: kirtib.bhanu39@gmail.com
- 🔗 Dataset: https://statso.io/carbon-emissions-worldwide-case-study/
