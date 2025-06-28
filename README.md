# Claims-Frequency-and-Severity-Modeling-Auto-Insurance-Pricing-UNED-Data-Science-
Applied modeling project focused on estimating claim frequency and severity for third-party material damages in car insurance. Includes data cleaning, EDA, predictive modeling with GLMs, and pure premium calculation.
# Claims Frequency and Severity Modeling – Auto Insurance Pricing (UNED Data Science)

This repository contains an applied data science project focused on modeling insurance claims for a Spanish non-life insurance company. It was developed as part of Module 7 – Big Data in the Insurance Sector, within the Master’s program in Big Data and Data Science Applied to Economics and Business (UNED, 2024–2025).

## 🎯 Objective

The aim of the project is to build two predictive models:
- A **frequency model** to estimate the number of material damage claims.
- A **severity model** to estimate the average claim cost.

The final result is the calculation of **pure premiums** based on real business logic and actuarial principles.

## 📊 Dataset Overview

The original dataset (`datosRiesgoCasoPracticoFinal.csv`) includes features related to:
- Policyholder characteristics (e.g., credit score, driving license age)
- Vehicle attributes (e.g., value, horsepower, usage)
- Geographic and contract information
- Claims history and exposure

## 🔍 Project Structure

- **EDA & Preprocessing**:  
  Data exploration, feature cleaning, recoding, and creation of new derived variables.

- **Modeling Process**:
  - GLMs fitted separately for claim frequency and severity
  - Model refinement through business interpretation and statistical significance
  - Selection of important predictors and final model calibration

- **Model Validation**:
  - Actual vs Expected (AvE) plots
  - General impact visualizations
  - Out-of-sample comparison (Modelling vs Validation sets)

- **Pure Premium Calculation**:
  - Combination of predicted frequency and average cost
  - Summary of distribution statistics (min, Q1, median, Q3, max, mean)

## ⚙️ Tools Used

- R, caret, ggplot2, dplyr, broom  
- RMarkdown for reproducible reporting  
- Actuarial and data science methodology  

## 📄 Output

The complete report is available in the file:  
📎 `Oscar_Porta_Modulo7_Frecuencia_Severidad.html`

## 👨‍💻 Author

Óscar Porta  
Master’s Student in Big Data & Data Science – UNED  
GitHub: [Oscar-Porta](https://github.com/Oscar-Porta)
