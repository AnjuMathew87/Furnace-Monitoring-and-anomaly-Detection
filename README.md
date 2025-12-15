a machine learning-based framework for predicting thermocouple 
temperatures and analysing feature importance in industrial furnaces. Utilizing high
frequency time-series data from two furnaces with six thermal zones, the study explores the 
effectiveness of both linear (Lasso, Ridge) and nonlinear (Random Forest, XGBoost, LSTM) 
models in forecasting localized and aggregated temperature behaviours. 
Results indicate that nonlinear models, particularly XGBoost, achieve superior accuracy and 
execution efficiency, making them ideal for real-time deployment in furnace operations. 
Feature interpretability is addressed using SHAP and LIME, which highlight critical process 
variables such as fuel flow rates, zone-level average temperatures, and line control speed. 
These insights provide valuable input for process optimization and predictive maintenance. 
An adaptive thresholding mechanism is implemented using residual-based confidence 
intervals, enabling dynamic and statistically grounded detection of sensor anomalies. The 
hierarchical approach by structuring models at the zone level, furnace level, and whole unit 
level, give engineers the flexibility to pinpoint anomalies with precision and explore 
thermocouple (TC) changes in specific areas. This adds a layer of adaptability that’s crucial for 
troubleshooting and operational decision-making. Additionally, the study evaluates the utility 
of transfer learning for model reuse across zones, finding it beneficial for data-limited settings. 
To enhance operational usability, an interactive Power BI dashboard is developed for real-time 
monitoring, visualization, and anomaly exploration. This end-to-end framework demonstrates 
how predictive modeling, interpretability, and visualization can be integrated to support 
smarter, data-driven furnace operations in industrial environments.
