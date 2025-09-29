<div align="center">
  <img src="https://img.shields.io/badge/Project-Diabetes_Prediction-blueviolet?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Model-Random_Forest_Classifier-informational?style=for-the-badge" />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-black?style=flat&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=jupyter" />
</div>

<h1 align="center">Predicting Diabetes and Health Risk Factors</h1>

<p align="center">
  This project focuses on predicting diabetes and identifying key health risk factors using a Random Forest Classifier. The analysis is based on a comprehensive dataset containing genetic, lifestyle, and health-related information.
</p>

---

## 👩‍💻 Project Members
- **ALFAIZZ DYANDARA ARDIN** (41523010176)
- **AMANDA PUSPITA SARI** (41523010047)

---

## 📂 Dataset
The analysis is performed on the `diabetes_dataset00.csv` file. This dataset includes a wide range of features, such as:
- Genetic Markers and Autoantibodies
- Family History and Environmental Factors
- Lifestyle Metrics (Age, BMI, Physical Activity, Dietary Habits, Smoking Status, Alcohol Consumption)
- Clinical Measurements (Blood Pressure, Cholesterol, Blood Glucose, Waist Circumference)
- Medical History (PCOS, Gestational Diabetes, Pancreatic Health, Cystic Fibrosis, Steroid Use)
- And other health-related variables.

---

## 🚀 Methodology

The project follows a structured machine learning pipeline to ensure robust and accurate predictions:

### 1. Data Loading & Pre-processing
- Initial checks for missing values, duplicates, and data types.
- Encoding of categorical features using Label Encoding.
- Splitting data into training and testing sets.
- Scaling numerical features with `StandardScaler` to standardize the data.

### 2. Feature Engineering & Selection
- **Random Forest Feature Importance** is used to rank and select the most relevant features.
- A **correlation heatmap** visualizes the relationships among the selected features.

### 3. Model Building & Training
- A **Random Forest Classifier** is trained on the pre-processed data.
- The model's initial performance is evaluated using accuracy, a classification report, and a confusion matrix.
- Feature importances from the trained model are visualized to understand feature contributions.

### 4. Hyperparameter Tuning & Evaluation
- **RandomizedSearchCV** is utilized to find the optimal hyperparameters for the model, enhancing its predictive power.
- The tuned model is re-evaluated to assess performance improvements.
- **Cross-validation** is performed to ensure the model's stability and reliability.
- Training and testing accuracies are compared to check for potential overfitting.
- A single decision tree from the final Random Forest model is visualized for interpretability.

---

## 📦 Requirements

To run this project, you need the following Python libraries. You can install them using `pip`:

```bash
pip install pandas scikit-learn matplotlib seaborn
