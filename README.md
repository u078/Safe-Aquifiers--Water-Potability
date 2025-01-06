# Safe-Aquifiers--Water-Potability

# Project Overview

- This project aims to develop predictive models for assessing the potability of water sources based on historical data and various water quality parameters. The goal is to help stakeholders make informed decisions to ensure access to safe drinking water. The project utilizes machine learning techniques to analyze water quality data and predict whether the water is potable.

# Installation and Setup

1. Install Anaconda: Download and install Anaconda from Anaconda's official website.
2. Open Anaconda Navigator: Launch Anaconda Navigator from your application menu or command line.
3. Open Jupyter Notebook: Click on the Jupyter Notebook icon in the Anaconda Navigator to open it in your web browser.
4. Create or Open a Notebook: Create a new notebook or open an existing one to start working with Python.

# Python Packages Used
The following Python packages are used in this project:

pandas - For data manipulation and analysis
numpy - For numerical computations
scikit-learn - For machine learning algorithms and evaluation metrics
matplotlib - For data visualization
seaborn - For statistical data visualization
catboost - For gradient boosting
lightgbm - For gradient boosting
xgboost - For gradient boosting

# Data

The dataset used in this project can be accessed on Kaggle and includes water quality metrics for 3,276 different water samples. Each sample is assessed for various parameters such as pH, hardness, solids, chloramines, sulfate, conductivity, organic carbon, trihalomethanes, and turbidity. The dataset also includes a binary target variable indicating water potability.

# Source Data

he dataset used in this project was sourced from Kaggle's Safe Acquifiers Dataset). Ensure you download the dataset and place it in the appropriate directory within the project folder.

# Results and Evaluation

The project evaluated several machine learning models, including Logistic Regression, Random Forest, and Gradient Boosting Classifier. Key results include:

Random Forest: Achieved the highest accuracy of 75.80% and an AUC of 0.8370. It consistently outperformed other models in terms of accuracy, precision, and F1-score.
XGBoost: Demonstrated strong performance with high recall and precision.
LightGBM: Showed improvement after hyperparameter tuning, achieving an accuracy of 75.68%.

# Future Work

- Expand the Dataset: Incorporate samples from more diverse regions to improve model generalizability.
- Model Enhancement: Explore advanced techniques and hyperparameter tuning to further enhance model performance.
- Integration: Implement the predictive model into water treatment facilities for real-time monitoring and early detection of contamination.
- Ethical and Bias Considerations: Ensure fairness and minimize biases in predictions to prevent disproportionate effects on certain populations.
