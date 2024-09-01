## *Project Overview*

This project focuses on predicting the risk of heart attacks using machine learning techniques. The prediction model is built based on 25 medical and lifestyle features such as age, cholesterol levels, blood pressure, and lifestyle habits. The dataset used in this project contains 8,763 records and was sourced from Kaggle.

## *Dataset*
- *Source*: The dataset is sourced from [Kaggle](https://www.kaggle.com/), a popular platform for datasets and data science competitions.
- *Description*: The dataset consists of 25 features related to patient demographics, medical history, lifestyle factors, and other relevant attributes. These features are used to predict the likelihood of a heart attack (heart attack risk).

- *Features*:
  1. Patient ID: Unique identifier for each patient
  2. Age: Age of the patient
  3. Sex: Gender of the patient (e.g., Male, Female)
  4. Cholesterol: Cholesterol level in mg/dl
  5. Blood Pressure: Blood pressure in mmHg
  6. Heart Rate: Heart rate in beats per minute (bpm)
  7. Diabetes: Whether the patient has diabetes (Yes/No)
  8. Family History: Family history of heart disease (Yes/No)
  9. Smoking: Smoking status (e.g., Current, Former, Never)
  10. Obesity: Obesity status (Yes/No)
  11. Alcohol Consumption: Alcohol consumption level (e.g., None, Moderate, High)
  12. Exercise Hours per Week: Hours of exercise per week
  13. Diet: Diet type (e.g., Balanced, High-fat, Low-carb)
  14. Previous Heart Problems: History of previous heart problems (Yes/No)
  15. Medication Use: Current use of heart-related medication (Yes/No)
  16. Stress Level: Self-reported stress level (e.g., Low, Medium, High)
  17. Sedentary Hours per Day: Hours spent in sedentary activities per day
  18. Income: Annual income level (e.g., Low, Medium, High)
  19. BMI: Body Mass Index (BMI) value
  20. Triglycerides: Triglyceride level in mg/dl
  21. Physical Activity Days per Week: Number of days per week with physical activity
  22. Sleep Hours per Day: Average sleep hours per day
  23. Country: Country of residence
  24. Continent: Continent of residence
  25. Hemisphere: Hemisphere of residence (Northern/Southern)
  26. Heart Attack Risk: Target variable indicating the risk of heart attack (e.g., Low, Medium, High)



### *Usage*
1. *Data Preprocessing*:
   - Run the data_preprocessing.py script or open the data_preprocessing.ipynb notebook to clean and prepare the data.
  
2. *Model Training*:
   - Train the model using train_model.py or model_training.ipynb. This will generate a trained model saved in the models/ directory.
  
3. *Model Evaluation*:
   - Evaluate the model's performance using evaluate_model.py or model_evaluation.ipynb.

4. *Prediction*:
   - Use the trained model to predict heart attack risk on new data by running the appropriate script/notebook.

### *Model Details*
- *Algorithms Used*: 
  - Logistic Regression
  - Random Forest
  - Support Vector Machine (SVM)
- *Evaluation Metrics*:
  - Accuracy
  - Precision
  - Recall
  - F1 Score
  - ROC-AUC Curve

### *Results*

the model has an accuracy of 64.4 percent.
