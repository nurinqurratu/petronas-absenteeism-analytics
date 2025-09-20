# Employee Absenteeism Analysis & Prediction (2025)

## 📌 Project Overview
This project analyses employee absenteeism data provided by the HRM department at **Petronas**.  
As part of my role as a **Data Analyst & Data Scientist**, I applied big data analytics and machine learning techniques to clean, analyse, and predict absenteeism trends to support strategies for improving employee productivity.  

---

## 📂 Dataset
- **File:** `Absenteeism_at_work_dataset2025.csv`  
- Contains missing values and noisy data (`#`).  
- Source: HRM Department (simulated dataset for analysis).  

---

## ⚙️ Data Cleaning
1. Converted `#` → `NaN`  
2. Imputed missing values using **mode**  
3. Simplified `Absenteeism time in hours` into categories:  
   - `1 = Time Slip (≤ 4 hours)`  
   - `2 = MC (5–72 hours)`  
   - `3 = Abnormal (> 72 hours)`  

---

## 📊 Analysis Tasks
- **Q1**: Counted missing values before cleaning  
- **Q2**: Calculated averages for *Hit target* and *Workload*  
- **Q3**: Distribution of absenteeism categories (bar chart)  
- **Q4**: Extracted abnormal records into a new CSV  
- **Q5**: Identified employees ≤ 35 y/o, ≥ 50KM away, with MC (pie chart)  
- **Q6**: Relationship between age & number of sons  
- **Q7**: Relationship between BMI & age  
- **Q8**: Transportation expense distribution (histogram with mean line)  

---

## 🤖 Machine Learning Model
- **Algorithm:** Random Forest Classifier  
- **Train Accuracy:** `1.0000`  
- **Test Accuracy:** `0.9859`  
- **Task:** Predict absenteeism category (1 = Time Slip, 2 = MC, 3 = Abnormal)  

---

## 🔮 Predictions (Sample)
- **Input A:** `[11,8,2,1,180,51,18,42,205917,92,0,1,0,1,0,0,89,170,31]` → **Category: Time Slip**  
- **Input B:** `[22,7,6,1,361,52,3,28,239554,97,0,1,1,1,0,4,80,172,27]` → **Category: MC**  
- **Input C:** `[15,12,3,2,160,12,14,34,280549,98,0,1,2,1,0,0,95,196,25]` → **Category: Abnormal**  

---
