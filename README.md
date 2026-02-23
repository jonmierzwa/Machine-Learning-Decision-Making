# Machine-Learning-Decision-Making
- Objective: Using a Random Forest classifier to predict if an individual is suffering from heart disease. Leverage SHAP and LIME to conduct deeper investigation into the ML model's decision making progress for each prediction.
- Dataset: Heart data taken from Kaggle site, consisting of more than 300 entries.
- Approach: Load in dataset, data cleaning, model building, evaluate performance, and use LIME/SHAP to understand model's decision making process. 
- Key Findings: The RF classifier did a solid job of predicting on the test set and yielded an accuracy rate of about 84%. The features with the most influence on the model's thought process were the severity of chest pain and patient's thalassemia levels. Through the use of SHAP/LIME plots, we were able to see each how feature can pull or push the model to predict a certain way.
