# Advancing Flood Susceptibility Mapping: Integrating Hydrology-Informed Synthetic Data and SHAP-Based Feature Selection

This repository presents a hydrology-informed framework for flood susceptibility mapping, with a case study in Jeddah, Saudi Arabia. The study addresses the challenge of limited flood inventory data by integrating constrained synthetic data generation with feature selection and machine learning models.

## Overview
Flood susceptibility mapping plays a critical role in disaster risk reduction, particularly in arid and semi-arid regions where hydrological observations are limited. This work proposes a framework that combines domain knowledge with data-driven techniques to enhance predictive performance under data scarcity conditions.

## Objectives
- Develop a robust flood susceptibility modeling framework for data-scarce environments  
- Incorporate hydrology-informed constraints into synthetic data generation  
- Identify influential flood conditioning factors using SHAP-based feature selection  
- Evaluate and compare machine learning models for susceptibility prediction  

## Methodology
The proposed workflow consists of the following stages:

1. Data preparation and preprocessing of flood conditioning factors  
2. Hydrology-informed synthetic data generation using SDV  
3. Statistical and machine learning-based evaluation of synthetic data  
4. Feature selection using SHapley Additive exPlanations (SHAP)  
5. Model development using:
   - CatBoost  
   - Multi-Layer Perceptron (MLP)  
6. Model evaluation using standard classification metrics  


## Data Availability
The real dataset used in this study is confidential and is not included in this repository. It was provided by a collaborator and cannot be publicly shared.

Access to the data may be considered upon reasonable request, subject to approval from the data provider. For inquiries, please contact: abeer.ibrahimf@gmail.com


## Author
Abeer Alfaifi  
Master’s Student in Computer Science  

## Acknowledgments
This work was conducted as part of a master’s thesis on flood susceptibility mapping. The hydrological constraints used in the synthetic data generation process were 
reviewed by experts at the National Center for Meteorology (NCM), Saudi Arabia.
