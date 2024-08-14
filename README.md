# SydneyIncidents

This research presents a comprehensive machine learning approach to predicting the duration of traffic incidents, classifying them as short-term or long-term, and understanding what are the factors that affect the duration the most. Our modelling methodology is using a dataset from the Sydney Metropolitan Area that includes detailed records of traffic incidents, road network characteristics, and socio-economic indicators, we train and evaluate a variety of advanced machine learning models including Gradient Boosted Decision Trees (GBDT), Random Forest, LightGBM, and XGBoost. The models are assessed using Root Mean Square Error (RMSE) for regression tasks and F1 score for classification tasks.

Our experimental results demonstrate that XGBoost and LightGBM outperform conventional models with XGBoost achieving the lowest RMSE of 33.7 for predicting incident duration and highest classification F1 score of 0.62 for a 30-minute duration threshold. For classification, the 30-minute threshold balances performance with 70.84\% short-term duration classification accuracy and 62.72\% long-term duration classification accuracy. Feature importance analysis, employing both tree split counts and SHAP values, identifies the number of affected lanes, traffic volume, and types of primary and secondary vehicles as the most influential features.

The proposed methodology not only achieves high predictive accuracy but also provides stakeholders with vital insights into local area factors contributing to incident durations.

The paper available by the link:
https://arxiv.org/pdf/2406.18861
