# Cardiovascular_Risk_Prediction
![image](https://github.com/Atharva070799/Cardiovascular_Risk_prediction_Classification/assets/130131832/9f8b07ef-b136-4ebf-89c5-41840b8525b2)


## **Problem Statement:**
Cardiovascular diseases (CVDs) are the major cause of mortality worldwide. According to WHO, 17.9 million people died from CVDs in 2019, accounting for 32% of all global fatalities.Though CVDs cannot be treated, predicting the risk of the disease and taking the necessary precautions and medications can help to avoid severe symptoms and, in some cases, even death. Machine learning techniques have shown promising results in improving the accuracy of cardiovascular risk prediction by integrating various risk factors and identifying non-linear interactions. However, there is a need for developing and validating machine learning models that can accurately predict cardiovascular risk using demographic, clinical, and laboratory data. The goal of this project is to address this need by developing and evaluating a machine learning model for predicting the 10-year risk of cardiovascular disease using the Heart Study dataset.

## Dataset
Dataset_Link:- https://drive.google.com/file/d/1k_UtJW3a3fsxANS973N3FAbEiKiL3f-7/view?usp=sharing
**Demographic:**

1) Age: Age of the patient.

2) Sex: male or female("M" or "F")

**Behavioral:**

3) is_smoking: whether or not the patient is a current smoker ("YES" or "NO").

4) CigsPerDay: the number of cigarettes that the person smoked on average in one day.(countinous type feature because a person can smoke 'n' times a day)

**Medical(history):**

5) BPMeds: whether or not the patient was on blood pressure medication.

6) Prevalent Stroke: whether or not the patient had previously had a stroke.

7) Prevalent Hyp: whether or not the patient was hypertensive.

8) Diabetes: whether or not the patient had diabetes.

**Medical(current):**

9) Tot Chol: total cholesterol level.

10) Sys BP: systolic blood pressure.

11) Dia BP: diastolic blood pressure.

12) BMI: Body Mass Index.

13) Heart Rate: heart rate.

14) Glucose: glucose level.

**Target feature(class of risk):**

15) TenYearCHD: 10-year risk of coronary heart disease CHD (“1”, means “Yes”, “0” means “No”)

## **Conclusion**
**Conclusion From EDA**

1) Age is a significant factor in determining CHD risk.

2) Men are more likely to develop CHD than women.

3) Smoking is a risk factor for CHD, and smoking intensity plays a role in determining the risk.

4) Patients with high blood pressure, stroke, and diabetes are at higher risk for CHD.

5) Patients who have had a prevalent stroke and prevalent hypertension are more likely to be at risk for CHD.

6) Patients with diabetes are also more likely to be at risk for CHD.

7) Total cholesterol levels are slightly higher in patients at risk for CHD.

8) There is a positive relationship between certain variables such as age and systolic blood pressure, BMI and glucose levels.

**Conclusion From Model Implementation**

1) Among the six models tested, the Random Forest Classifier and XGBoost models performed the best, with high accuracy, precision, and recall scores.

2) While the KNN model had a relatively high recall score, its accuracy and precision scores were lower than those of the Random Forest Classifier and XGBoost models.

3) The SVC model had a lower accuracy and ROC AUC score, indicating that it may not be as suitable for this particular classification problem.

4)The XGBoost model had slightly higher test accuracy and precision scores than the Random Forest Classifier, and a higher ROC AUC score, suggesting that it may be a better choice for predicting cardiovascular risk.

5) Based on the results presented, the Random Forest Classifier model was chosen as the best fit classification model for the cardiovascular risk prediction dataset having accuracy of 89.06%.
