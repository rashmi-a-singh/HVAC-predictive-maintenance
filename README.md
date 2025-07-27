HVAC Predictive Maintenance Model
Project Overview

This project addresses a critical business need: preventing unplanned equipment downtime. I developed a binary classification model that predicts the likelihood of an HVAC unit failing within a given timeframe based on its operational sensor data. By anticipating failures, this model enables proactive maintenance, which can save companies millions in repair costs and lost productivity.

This project demonstrates an end-to-end machine learning workflow, from raw time-series data processing to model training and performance evaluation.
Key Technical Skills :
-Data Processing & Feature Engineering: Used Pandas to process time-series data, calculating Remaining Useful Life (RUL) and engineering a binary target variable for classification.

-Machine Learning Modeling: Trained and evaluated a LightGBM (LGBM) Classifier, a powerful gradient boosting framework ideal for this type of predictive task.

-Model Evaluation: Assessed model performance using accuracy, precision, recall, and a confusion matrix to understand the model's effectiveness in catching potential failures while minimizing false alarms.

-Programming & Tools: The entire project was built in Python using libraries like Scikit-learn, Pandas, NumPy, and Matplotlib/Seaborn.

    
Data Source

The model was trained on the NASA Turbofan Engine Degradation Simulation Dataset. This public dataset serves as a robust proxy for real-world industrial machine--in this case, HVAC compressor units running to the point of failure.
Dataset : [NASA CMAPS Data Set on Kaggle](url)

Performance & Results

The final model achieved an overall accuracy of 96.1% on the unseen test set. The confusion matrix below shows that the model is highly effective at identifying imminent failures (True Positives) while maintaining a low rate of false alarms.

This demonstrates the model's potential as a reliable tool for a predictive maintenance strategy.
