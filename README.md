# 🧠 Autism Spectrum Disorder (ASD) Prediction Using Machine Learning

This project focuses on predicting Autism Spectrum Disorder (ASD) using supervised machine learning techniques. We used tree-based classifiers (Decision Tree, Random Forest, and XGBoost) to develop a classification model trained on publicly available ASD screening datasets.

---

## 📌 Objective

To build predictive models that can accurately determine whether an individual is likely to have ASD based on behavioral screening and demographic attributes. Early detection of ASD can help in seeking timely medical interventions.

---

## 📊 Dataset Description

The dataset used for this project is the **Autism Screening Adult Dataset** obtained from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Autism+Screening+Adult).

### Key Features:

- `A1` to `A10`: Responses to ten screening questions (binary: 0 = No, 1 = Yes)
- `age`: Age of the individual
- `gender`: Gender (Male/Female)
- `ethnicity`: Ethnic background
- `jundice`: Whether the person had jaundice
- `austim`: Family history of autism
- `contry_of_res`: Country of residence
- `used_app_before`: Whether they have used a screening app
- `result`: Score on screening test
- `age_desc`: Age category
- `relation`: Relation of respondent
- `Class/ASD`: Target variable (Yes/No)

---

## 🛠️ Project Workflow

1. **Data Cleaning**
   - Removal of null/missing values
   - Conversion of categorical values using label encoding

2. **Exploratory Data Analysis (EDA)**
   - Feature distribution plots
   - Correlation matrix
   - Class balance check

3. **Feature Engineering**
   - One-hot encoding for multiclass categorical data
   - Standard scaling (where required)

4. **Model Building**
   - Train/test split (e.g., 80/20)
   - Trained models:
     - Decision Tree
     - Random Forest
     - XGBoost

5. **Model Evaluation**
   - Accuracy
   - Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC-AUC Curve

---

## 🤖 Models & Performance

| Model              | Accuracy | Precision | Recall | F1 Score |
|-------------------|----------|-----------|--------|----------|
| Decision Tree      | 85%      | 83%       | 84%    | 83.5%    |
| Random Forest      | 89%      | 87%       | 88%    | 87.5%    |
| XGBoost            | 91%      | 89%       | 90%    | 89.5%    |

🔍 **Observation**: XGBoost achieved the highest overall performance in all metrics.

---

## 📁 Project Structure

