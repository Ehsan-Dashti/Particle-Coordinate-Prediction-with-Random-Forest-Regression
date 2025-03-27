# Particle-Coordinate-Prediction-with-Random-Forest-Regression
🧪 Particle Coordinate Prediction with Random Forest Regression
This repository contains our DSL Winter Project 2024 aimed at predicting the (x, y) coordinates of particles passing through a Resistive Silicon Detector (RSD) using machine learning techniques. The detector, equipped with 12 pads, generates signals that are transformed into features such as pmax, negpmax, tmax, area, and rms.

🚀 Highlights
🔍 Data Preprocessing: Identified and removed noisy columns through statistical analysis and feature-target correlation, reducing noise from sensor constraints.

🛠️ Feature Engineering: Generated polynomial feature combinations (squares and cubes) to enhance model learning.

🌲 Model: Implemented a Random Forest Regressor within a MultiOutputRegressor wrapper to predict both coordinates simultaneously.

🎯 Hyperparameter Tuning: Combined GridSearchCV and RandomizedSearchCV for optimal parameter selection.

🏆 Performance: Achieved a Euclidean distance score of 4.736 on the leaderboard, outperforming the baseline of 6.629 (28.5% improvement).

📁 Files
main train validation and test.ipynb: Jupyter Notebook for preprocessing, training, and evaluation.

DSL_Report1.pdf: Detailed project report outlining problem analysis, methodology, experiments, and results.

📊 Techniques Used
Random Forest Regression

Feature correlation & noise detection

Multi-output regression

Polynomial feature augmentation

Hyperparameter optimization
