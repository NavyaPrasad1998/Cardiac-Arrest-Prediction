# Cardiac-Arrest-Prediction
Predicting Cardiact Arrest using Machine Learning 


## **Overview**
This project focuses on predicting Coronary Heart Disease (CHD) using a comprehensive healthcare dataset. By leveraging machine learning techniques, feature engineering, and statistical analysis, the study identifies key predictors of CHD and evaluates the effectiveness of various classification models.

---

## **Objectives**
1. **Predict Coronary Heart Disease (CHD):**  
   Develop a machine learning model to accurately predict CHD based on patient demographics, medical history, and biochemical metrics.
2. **Feature Selection and Analysis:**  
   Identify the most significant predictors of CHD using statistical and machine learning methods.
3. **Handle Class Imbalance:**  
   Apply techniques like **SMOTE** and **RandomUnderSampler** to balance the dataset for improved model performance.
4. **Model Evaluation:**  
   Evaluate multiple classification algorithms to determine the best-performing model for CHD prediction.

---

## **Dataset**
The dataset includes 37,079 patient records with 51 features, such as:
- **Demographics:** Age, Gender, Family Income
- **Vitals:** Pulse Rate, Systolic/Diastolic Blood Pressure
- **Biochemical Markers:** Glycohemoglobin, Triglycerides, Uric Acid
- **Health Indicators:** Diabetes, Family History of Stroke/Diabetes

---

## **Methodology**
1. **Data Preprocessing:**
   - Handled class imbalance using **SMOTE** and **RandomUnderSampler**, resulting in a balanced dataset of 30,160 samples.
   - Scaled features using **StandardScaler** for optimal model performance.

2. **Feature Selection:**
   - Applied **SelectKBest** (chi-square test) and **Random Forest Feature Importance** to identify 13 key features, including **Age**, **Diabetes**, **Glycohemoglobin**, and **Creatinine**.

3. **Exploratory Data Analysis (EDA):**
   - Visualized data distributions, correlations, and relationships using **heatmaps**, **violin plots**, and **interactive visualizations** with **Plotly**.
   - Conducted hypothesis testing to understand significant differences between CHD and non-CHD groups.

4. **Model Training and Evaluation:**
   - Trained and evaluated multiple models, including:
     - **Random Forest Classifier**
     - **Gradient Boosting Classifier**
     - **Support Vector Machine (SVM)**
     - **Logistic Regression**
     - **K-Nearest Neighbors (KNN)**
   - Measured performance using metrics such as **accuracy**, **F1-score**, and **ROC-AUC**.

---

## **Key Findings**
- **Top Predictors of CHD:**
  - **Age** and **Diabetes** were the most influential factors for CHD prediction.
  - **Glycohemoglobin** and **Creatinine** levels significantly differed between CHD and non-CHD groups (p < 0.05).

- **Model Performance:**
  - **Random Forest Classifier** achieved the highest accuracy (91.2%) and F1-score (91.3%), followed by **KNN** and **Gradient Boosting**.
  - Models were evaluated using **ROC curves** to assess classification performance.

---

## **Technologies Used**
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Imbalanced-learn
- **Techniques:** SMOTE, Feature Importance, Chi-Square Test, Hypothesis Testing
- **Models:** Random Forest, SVM, Logistic Regression, Gradient Boosting, KNN

---

## **Future Work**
1. Incorporate additional clinical and lifestyle factors for deeper analysis.
2. Experiment with deep learning models for more complex prediction scenarios.
3. Conduct longitudinal studies to track CHD progression over time.

