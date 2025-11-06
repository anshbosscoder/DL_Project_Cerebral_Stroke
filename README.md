# 🧠 DL_Project_Cerebral_Stroke

This project presents a **Cerebral Stroke Prediction Model** built using a **Sequential Artificial Neural Network (ANN)** to assist medical professionals in assessing patient stroke risk. The model leverages health-related data to enable **accurate and early prediction** of stroke likelihood.

---

## 📘 Overview

Cerebral stroke is a critical medical condition that requires timely diagnosis and prediction. This project applies **Deep Learning techniques** to analyze patient health data and predict the probability of stroke occurrence. The model can help healthcare providers make data-driven decisions and potentially improve patient outcomes.

---

## ⚙️ Key Features

- **Framework:** TensorFlow / Keras (Sequential ANN)  
- **Optimizer:** Adam  
- **Loss Function:** Binary Cross-Entropy  
- **Evaluation Metric:** Accuracy Score  
- **Data Analysis:** Pandas (for data cleaning, exploration, and preprocessing)  

---

## 🧩 Model Description

The ANN model is designed to **learn complex relationships** among various health attributes such as:

- Age  
- Hypertension  
- Body Mass Index (BMI)  
- Glucose Levels  
- Heart Disease  
- Smoking Status  

Using these factors, the model predicts the **likelihood of stroke occurrence** with high accuracy.

---

## 🧠 Project Workflow

1. **Data Collection & Loading** – Gathered patient health data for training.  
2. **Data Preprocessing** – Cleaned and normalized data using Pandas and NumPy.  
3. **Model Building** – Constructed a Sequential ANN with multiple dense layers.  
4. **Training & Validation** – Used the Adam optimizer and Binary Cross-Entropy loss.  
5. **Evaluation** – Measured model accuracy and performance on test data.  
6. **Prediction** – Model predicts stroke risk based on new input data.  

---

## 📊 Results & Insights

The model demonstrates effective learning and generalization ability on the dataset. It identifies patterns that correlate patient health parameters with stroke risk. This aids medical practitioners in understanding potential risk factors and taking preventive actions.

---

## 🚀 Future Scope

- Integrate with **real-time medical databases** for live data prediction.  
- Enhance **model interpretability** using **SHAP** or **LIME** to make predictions clinically explainable.  
- Implement a **web-based dashboard** for doctors to input patient data and view risk scores interactively.  

---

## 🧰 Technologies Used

| Category | Tools / Libraries |
|-----------|-------------------|
| Programming Language | Python |
| Deep Learning Framework | TensorFlow / Keras |
| Data Processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Evaluation Metrics | Accuracy Score |

---

## 📈 Example Output

```python
Input: { age: 67, hypertension: 1, bmi: 30.5, avg_glucose_level: 120.3 }
Predicted Output: Stroke Risk = 0.78 (High)
DL_Project_Cerebral_Stroke/
│
├── data/                     # Dataset used for training and testing
├── models/                   # Saved trained models
├── notebooks/                # Jupyter notebooks for experiments
├── src/                      # Source code files
├── requirements.txt           # Required libraries
├── README.md                  # Project documentation
└── stroke_prediction.py       # Main Python script
