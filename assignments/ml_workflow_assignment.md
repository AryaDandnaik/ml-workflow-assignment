# ML Workflow Assignment

## Task 1 — Label and Data Leakage

**Label Column:**  
repeat_purchase_flag  

**Justification:**  
This column represents the target variable we want to predict (whether a customer makes a repeat purchase within 30 days).

---

**Data Leakage Column:**  
discount_used_on_repeat_order  

**Justification:**  
This column contains information that is only available after the repeat purchase happens, so using it would leak future information into the model and lead to unrealistic performance.

---

## Task 2 — Missing Steps in ML Workflow

### Step 1: Exploratory Data Analysis (EDA)

**Why it matters:**  
EDA helps understand data patterns, detect missing values, identify outliers, and understand relationships between features and the target.

---

### Step 2: Data Preprocessing & Feature Engineering

**Why it matters:**  
This step includes handling missing values, scaling data, encoding variables, and removing leakage features. Without this, the model may give incorrect results.

---

## Conclusion

A proper ML workflow requires understanding and preparing the data before applying models. Skipping these steps leads to poor and unreliable predictions.
