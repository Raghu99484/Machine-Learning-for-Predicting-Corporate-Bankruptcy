# Machine Learning for Predicting Corporate Bankruptcy
## Project Overview
This project explores the application of machine learning (ML) techniques to predict corporate bankruptcy, a critical challenge in financial analytics. Utilizing a dataset that spans from 2000 to 2023 and contains financial ratios and indicators of 92,872 companies, we develop and evaluate Logistic Regression and Random Forest models to forecast financial distress.

## Objectives
- Develop ML Models: To employ Logistic Regression and Random Forest algorithms for bankruptcy prediction, leveraging their classification capabilities.
- Model Comparison: To assess the models' performance using accuracy, precision, recall, and F1-score, and to discuss their interpretability.
- Exploratory Data Analysis (EDA): To conduct EDA for insights into the dataset's characteristics, including class imbalance and feature correlations.
## Dataset Overview
The dataset comprises 12 financial features and one target variable indicating bankruptcy. It includes metrics like EPS, Liquidity, Profitability, and more, alongside a binary target that classifies companies into bankrupt or non-bankrupt categories. Key challenges addressed include class imbalance, outliers, and missing values.

## Methodology
- Data Processing: Implementation of winsorization to handle outliers and median imputation for missing values, preparing a normalized dataset for modeling.
- Model Training: Application of Logistic Regression and Random Forest, with hyperparameter tuning for the latter to optimize performance.
- Evaluation and Comparison: Use of confusion matrices and classification reports to evaluate model outcomes, focusing on their practical applications in financial decision-making and risk management.
## Key Findings
- Logistic Regression: Exhibited high recall but low precision for bankrupt cases, indicating effectiveness in identifying potential bankruptcies at the cost of higher false positives.
- Random Forest: Demonstrated high accuracy for non-bankrupt predictions but struggled with the minority bankrupt class, reflecting challenges in dealing with imbalanced data.
- Model Insights: Logistic Regression offers valuable interpretability for financial indicators, whereas Random Forest excels in handling complex data relationships.
## Practical Applications
- Credit Risk Assessment: For evaluating the bankruptcy risk in lending decisions.
- Investment Strategy: To inform risk profiles in investment decisions.
- Regulatory Oversight: For monitoring financial stability and compliance.
- Portfolio Management: To guide asset management and investment diversification.
## Future Directions
- Advanced ML Techniques: Exploration of Gradient Boosting and Deep Learning models.
- Data Augmentation: Inclusion of macroeconomic indicators to enhance model robustness.
- Custom Model Development: Tailoring algorithms to specific financial contexts and risk management strategies.
