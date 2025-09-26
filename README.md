# Solar Still Performance Analysis

## 🌍 Overview

This project focuses on analyzing the performance of a **solar still** system, an effective solution for addressing global freshwater scarcity using renewable energy. With the growing demand for clean water and energy, solar stills offer a sustainable method for water purification by utilizing solar energy.

> It is estimated that by 2050, more than two-thirds of the world’s population will face water shortages, affecting both developing and developed nations. As freshwater resources diminish, the integration of **renewable energy** with **water purification technologies** becomes increasingly crucial. Solar stills stand out as a promising solution, offering a low-cost, eco-friendly method for producing potable water using solar radiation.

## 🎯 Objective

The goal of this study is to analyze and predict the **water productivity per unit area (mw in L/m²)** and **thermal energy efficiency** of a solar still based on various environmental and operational parameters.

## 📊 Dataset Description

The dataset contains time-series measurements collected from a solar still experiment. Each row corresponds to a specific day and time with the following features:

### 🔢 Input Features:
- `Day`: Experiment day  
- `Time`: Time of the measurement  
- `Solar irradiance (W/m²)`: Solar radiation intensity  
- `Inner glass temperature`: Temperature of the inner glass surface  
- `Outer glass temperature`: Temperature of the outer glass surface  
- `Basin water temperature`: Temperature of the water in the basin  
- `Fresh water production (ml)`: Amount of water produced  
- `Ambient temperature`: Surrounding air temperature  
- `Area (m²)`: Surface area of the solar still  

### 🎯 Output Targets:
- `mw (L/m²)`: Water productivity per unit area  
- `Thermal energy efficiency`: Efficiency of converting solar energy into thermal energy for water distillation  

## 🛠️ Usage

This repository enables users to:

-Analyze how solar and thermal parameters affect water output and thermal energy efficiency using advanced regression techniques.
-Develop and evaluate machine learning models—including SVR, XGBoost, Random Forest, and Neural Networks—to predict water productivity and thermal efficiency from experimental data.
-Apply ensemble modeling and log-transformation strategies to improve prediction accuracy.
-Assess model performance with comprehensive evaluation metrics such as MAE, RMSE, R², and more.
-Visualize actual vs. predicted results with detailed series and scatter plots for both training and test datasets.
