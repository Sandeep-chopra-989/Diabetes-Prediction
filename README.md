# 🩺 Diabetes Prediction

This project aims to predict the likelihood of diabetes in individuals based on various health metrics. Utilizing machine learning algorithms, the goal is to assist healthcare professionals in early diagnosis and intervention.

---

## 📂 Dataset

- **Source**: [Kaggle - Diabetes Dataset by Akshay Dattatray Khare](https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset)
- **Description**: The dataset contains diagnostic measurements to predict whether a patient has diabetes.
- **Features**:
  - `Pregnancies`: Number of pregnancies
  - `Glucose`: Plasma glucose concentration
  - `BloodPressure`: Diastolic blood pressure (mm Hg)
  - `SkinThickness`: Triceps skinfold thickness (mm)
  - `Insulin`: 2-Hour serum insulin (mu U/ml)
  - `BMI`: Body mass index (weight in kg/(height in m)^2)
  - `DiabetesPedigreeFunction`: Diabetes pedigree function
  - `Age`: Age in years
  - `Outcome`: Class variable (1 if diabetic, 0 if non-diabetic)

---

## 🎯 Objective

To develop a machine learning model that can:
- Classify individuals as diabetic or non-diabetic based on health metrics.
- Provide insights into factors influencing diabetes risk.

---

## ⚙️ Technologies Used

- **Python 3**
- **Libraries**:
  - `pandas`, `numpy` – Data manipulation
  - `matplotlib`, `seaborn` – Data visualization
  - `scikit-learn` – Machine learning algorithms and evaluation
- **Jupyter Notebook** – Development environment

---

## 🔄 Data Processing & Analysis

1. **Data Cleaning**:
   - Handle missing or zero values in health metrics.
   - Normalize or standardize data as needed.

2. **Exploratory Data Analysis (EDA)**:
   - Visualize distributions of features.
   - Analyze correlations between features.

3. **Model Development**:
   - Split data into training and testing sets.
   - Train models using algorithms such as Logistic Regression, Random Forest, and Support Vector Machine.

4. **Model Evaluation**:
   - Evaluate models using metrics like accuracy, precision, recall, and F1-score.
   - Plot confusion matrix and ROC curve.

---

## 📊 Key Insights

- **Top Predictive Features**: Identified that `Glucose`, `BMI`, and `Age` are strong indicators of diabetes risk.
- **Model Performance**: Achieved high accuracy with Random Forest and Support Vector Machine models.
- **Recommendations**: Emphasized the importance of regular monitoring of blood glucose levels and maintaining a healthy BMI.

---

## 📚 Learning Outcomes

- Gained experience in data preprocessing and feature engineering.
- Developed skills in applying machine learning algorithms for classification tasks.
- Enhanced understanding of healthcare analytics and predictive modeling.

---
## 🙋‍♂️ Author
Sandeep
B.Tech in Information Technology
Data Science & Machine Learning Enthusiast


# License
This project is licensed under the MIT License. See the LICENSE file for more details.
