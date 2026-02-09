# Traffic Analysis – Namakkal District

## 📌 Project Overview
This project focuses on traffic data preprocessing and analysis for **Namakkal District**.  
The aim is to clean raw traffic data and prepare it for machine learning and data analysis tasks.

---

## 📂 Dataset Details

### 🔹 Raw Dataset
**File:** `namakkal_traffic_1500rows_25columns_uncleaned.csv`

**Description:**  
This file contains the original, unprocessed traffic data collected for Namakkal District.

**Issues in Raw Data:**
- Missing values  
- Categorical (text) data  
- Different value ranges  

---

### 🔹 Preprocessed Dataset
**File:** `second_dataset_place_updated.csv`

**Description:**  
This file contains the cleaned and transformed version of the raw dataset, ready for analysis and machine learning.

---

## ⚙️ Data Preprocessing Steps
- Missing values were handled  
- Numerical columns filled using mean  
- Categorical columns filled using mode  
- Categorical features converted into numerical values using label encoding  
- Feature scaling applied using **Min-Max normalization (0–1 range)**  

---

## 🛠️ Tools and Technologies Used
- Python  
- Pandas  
- Scikit-learn  
- GitHub  

---

## 🚀 Applications
- Traffic congestion prediction  
- Accident risk analysis  
