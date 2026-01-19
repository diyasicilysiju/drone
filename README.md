Project Overview

Unmanned Aerial Vehicles (UAVs), commonly known as drones, are widely used in civilian and military applications such as surveillance, mapping, and logistics. However, unauthorized or unidentified drones pose serious security threats in sensitive environments, especially during high-risk military operations. Rapid drone assessment and the selection of an appropriate countermeasure are critical for ensuring operational safety.

This project presents a data-mining-based drone countermeasure recommendation system that predicts the most suitable response action for an unidentified drone based on its observed characteristics and behavior.

Objectives
To analyze drone signatures, flight behavior, payload indicators, and environmental conditions
To predict the most appropriate countermeasure for a detected drone
To demonstrate the role of data mining and machine learning in automated defence decision-making.
Dataset Description

Due to security restrictions, real-world operational drone datasets are not publicly available. Therefore, a simulated dataset of 1000 drone records was generated using statistical distributions and feature patterns inspired by the CRUW Drone Dataset.

Reference dataset: https://www.cruwdataset.org/home

Features Included
Drone Signatures:
RCS, Thermal_IR, RF_power, Metallic_index
Flight Parameters:
Altitude, Speed, Acceleration, Turn_rate
Payload Indicators:
Payload_weight, Heatmap_anomaly, Payload_metallic_index
Environmental Attributes:
Weather, Wind_speed, GPS_zone, Visibility
Target Label:
Recommended_countermeasure
Countermeasure Classe
Monitor
Jam
Directed Energy Weapon
Intercept


Data Analysis and Preprocessing

A comprehensive statistical analysis was performed to understand data distribution and detect inconsistencies.
Statistical Techniques
Mean, Median, Variance
Standard Deviation, IQR
Five-number summary
Distance and similarity measures
Visualization
Distribution plots
Quantile plots
Q–Q plots
Preprocessing Steps
Handling missing values
Encoding categorical features
Outlier capping using the IQR rule
Feature scaling and normalization


Machine Learning Models

The following classification algorithms were implemented:
Naive Bayes
Decision Tree
Support Vector Machine (RBF kernel)

Model Evaluation
Models were evaluated using:
Holdout validation
10-Fold Cross-Validation

Performance Metrics:
Accuracy
Precision
Recal
F1-score
Specificity
Error rate
Confusion matrices
Macro-AUC (ROC)
The model with the highest accuracy and consistent cross-validation performance was selected as the final classifier.

Applications
Military surveillance and defence zones
Border security systems
Critical infrastructure protection
Automated defence decision-support systems

Conclusion
This project demonstrates how data mining and machine learning techniques can enhance automated drone surveillance and defence decision-making. The proposed system provides a foundation for intelligent, real-time countermeasure selection in high-security environments.
