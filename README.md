Predicting Diabetes and Health Risk Factors Using Random Forest Classifier
This project focuses on predicting diabetes and identifying key health risk factors using a Random Forest Classifier. The analysis is based on a dataset containing genetic, lifestyle, and health-related information.

Project Members
ALFAIZZ DYANDARA ARDIN (41523010176)
AMANDA PUSPITA SARI (41523010047)
Dataset
The dataset used in this project is diabetes_dataset00.csv. It contains various features related to genetic markers, autoantibodies, family history, environmental factors, insulin levels, age, BMI, physical activity, dietary habits, blood pressure, cholesterol levels, waist circumference, blood glucose levels, ethnicity, socioeconomic factors, smoking status, alcohol consumption, glucose tolerance test results, history of PCOS, previous gestational diabetes, pregnancy history, weight gain during pregnancy, pancreatic health, pulmonary function, cystic fibrosis diagnosis, steroid use history, genetic testing results, neurological assessments, liver function tests, digestive enzyme levels, urine test results, birth weight, and early onset symptoms.

Methodology
The project follows these steps:

Data Loading and Initial Check: The dataset is loaded and checked for missing values, duplicates, and data types.
Data Description: Basic statistical descriptions of numerical and categorical features are provided.
Encoding Categorical Data: Categorical features are converted into numerical representations using Label Encoding.
Data Pre-processing:
The data is split into training and testing sets.
Numerical features are scaled using StandardScaler.
Class imbalance in the target variable is checked.
Data Construction (Feature Engineering/Selection):
Random Forest Feature Importance is used to identify the most relevant features for prediction.
A correlation heatmap of the selected features is generated.
The shapes of the selected feature sets are displayed.
Model Building and Training:
A Random Forest Classifier is trained on the training data.
The model's performance is evaluated using accuracy, classification report, and confusion matrix.
Feature importances from the trained model are visualized.
Hyperparameter Tuning:
RandomizedSearchCV is used to find the best hyperparameters for the Random Forest model.
The model is re-trained with the best hyperparameters.
The accuracy of the tuned model is evaluated.
Model Selection and Evaluation:
The classification report and confusion matrix for the tuned model are displayed.
Cross-validation is performed to assess model stability.
Overfitting is checked by comparing training and testing accuracy.
A single tree from the trained Random Forest is visualized.
Requirements
To run this notebook, you will need the following Python libraries:

pandas
scikit-learn
matplotlib
seaborn
You can install them using pip:
