# 🫀 Heart Attack Prediction Using Machine Learning

This project predicts the risk of a heart attack using machine learning based on medical, lifestyle, and demographic factors. It includes complete data preprocessing, exploratory data analysis (EDA), feature encoding, model training, model evaluation, and a deployed Gradio interface for real-time predictions.

---

## 📌 Project Overview

Cardiovascular diseases are among the leading causes of death globally. Early detection of heart attack risk can enable preventive healthcare and improve patient outcomes.  
This project uses machine learning algorithms to classify individuals into **Low Risk** or **High Risk** categories based on 24 health-related parameters.

---

## 📊 Dataset Features

The model uses the following 24 features:

- age  
- gender  
- income_level  
- hypertension  
- diabetes  
- cholesterol_level  
- obesity  
- waist_circumference  
- family_history  
- smoking_status  
- physical_activity  
- dietary_habits  
- air_pollution_exposure  
- stress_level  
- sleep_hours  
- blood_pressure_systolic  
- blood_pressure_diastolic  
- fasting_blood_sugar  
- cholesterol_hdl  
- cholesterol_ldl  
- triglycerides
- EKG_results  
- previous_heart_disease  
- medication_usage  

**Target:** heart_attack (0 = No, 1 = Yes)

---

## 🧠 Machine Learning Models Used

The following models were trained and compared:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Gradient Boosting Classifier  
- SVM  
- KNN   

✅ **Gradient Boosting Classifier performed the best and is used as the final model.**

---

## 🧹 Data Preprocessing

The project includes:

- Handling missing values  
- Removing irrelevant or duplicate features  
- Encoding categorical attributes  
- Fixing skewness (Log / Box-Cox transformations)  
- Outlier removal using IQR method  
- Feature scaling  

---

## 📈 Model Evaluation

Evaluation metrics used:

- Accuracy Score  
- Confusion Matrix  
- Precision, Recall, F1-Score
- Classification report  
- AUC Score
- ROC Curve

---

## 🖥️ Gradio Deployment

The project includes a simple and interactive **Gradio web interface** where users can input parameters to predict heart attack risk.

**Outputs:**
-  The Assessment shows a High Probability of Heart Attack 🫀  
-  The Assessment shows a Low probability of Heart Attack 🫀

---



