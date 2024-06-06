# Cardiovascular Disease (CVDs) and Heart Failure Prediction Dataset

Cardiovascular disease (CVDs) is the number one cause of death globally, taking an estimated 17.9 million lives each year, which accounts for 31% of all deaths worldwide. Four out of five CVD deaths are due to heart attacks and strokes, and one-third of these deaths occur prematurely in people under 70 years of age. Heart failure is a common event caused by CVDs.

People with cardiovascular disease or who are at high cardiovascular risk (due to the presence of one or more risk factors such as hypertension, diabetes, hyperlipidaemia or already established disease) need early detection and management.

This dataset contains 11 features that can be used to predict possible heart disease.

Let's train a machine learning model to assist with diagnosing this disease.

## Attribute Information

- **Age**: age of the patient [years]
- **Sex**: sex of the patient [M: Male, F: Female]
- **ChestPainType**: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- **RestingBP**: resting blood pressure [mm Hg]
- **Cholesterol**: serum cholesterol [mm/dl]
- **FastingBS**: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- **RestingECG**: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- **MaxHR**: maximum heart rate achieved [Numeric value between 60 and 202]
- **ExerciseAngina**: exercise-induced angina [Y: Yes, N: No]
- **Oldpeak**: oldpeak = ST [Numeric value measured in depression]
- **ST_Slope**: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- **HeartDisease**: output class [1: heart disease, 0: Normal]

## Data Source

The dataset was sourced from [Kaggle](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction).

In this repository, we have conducted analysis and predictions using the Random Forest classifier. The following steps were performed:

- **Data Preprocessing**: The dataset was preprocessed to handle missing values and encode categorical features. Numerical features were also scaled for optimal performance of the machine learning model.
- **Model Training**: A Random Forest classifier was trained on the preprocessed dataset.
- **Model Evaluation**: The trained model was evaluated using cross-validation and performance metrics such as accuracy, recall, precision, and F1 score.
- **Predictions**: Predictions were made on the test set using the trained Random Forest model achieving promising results.
- **Feature Importance**: Feature importances were extracted from the trained model to identify the most influential features in predicting heart disease.


## For future improvements

While efforts have been made to provide accurate analysis and predictions, there may be areas for improvement or alternative approaches that could yield better results.

- With a larger dataset and possibly numerical fasting blood sugar values without an imposed threshold, better results could be achieved.
- Additionally, with more features and data, exploring the application of deep learning models, such as neural networks, could be beneficial.
- Suggestions for enhancements, corrections, or alternative methodologies are welcome and encouraged.
