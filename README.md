# Predict the CO2 emissions of Seattle's buildings

### Overview : Supervised learning to predict the CO2 emissions of Seattle non-residential buildings.  

Typical cleanings (imputations, drops, outliers mitigation) are realized on the dataset, and residential buildings are removed. Feature engineering uses common sense, statistics, encodings, standardizations, and dimensionality reduction (PCA) techniques.

Features are selected statistically (multicollinearity is mitigated with the variance inflation factor, contingency tests, and ANOVA tests). The dataset is prone to data leakage. Some features are removed accordingly.
R2 and RMSE metrics are used to evaluate the performance of the models. 

Are implemented, trained (with cross-validation), and optimized (grid search): Linear regression models, a Support Vector Machines model, a K Nearest Neighbors model, a Random Forest model, an Additive Boosting model, and an XGBoost model. The XGBoost model is the model selected.
