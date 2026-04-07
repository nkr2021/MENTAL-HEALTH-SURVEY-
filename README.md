# 🧠 Mental Health in Tech - Exploratory Data Analysis (EDA)

This project explores mental health trends in the tech industry using survey dataset. The goal is to identify patterns related to treatment-seeking behavior and the influence of demographics and workplace factors on mental health support.

---

## 📁 Dataset
- **Source:** SERVEY.CSV
- **Rows:** 1259
- **Features:** Age, Gender, Country, Treatment, Family History, Remote Work, Employer Support, etc.

---

## 📊 Key EDA Tasks Performed

### ✅ Data Cleaning
- Removed unrealistic age entries (<16 or >100)
- Standardized gender entries into `male`, `female`, `trans`, and `other`

### 📍 Univariate Analysis
- Age distribution
- Gender distribution
- Treatment and family history counts

### 📍 Bivariate Analysis
- Gender vs Treatment
- Family History vs Treatment
- Work Interference vs Treatment

### 🌍 Country-Level Analysis
- Top 10 countries by treatment count

### 🏢 Workplace Factors
- Mental health benefits vs Treatment
- Knowledge of care options vs Treatment
- Anonymity vs Treatment

### 📈 Age Group Analysis
- Raw treatment counts by age group
- ✅ Bonus: **Percentage of treatment by age group**

---

## 📘 Key Insights

- Majority of respondents are aged 25–35 and identify as male
- Over 60% have sought treatment for mental health issues
- Treatment-seeking is higher among those with a family history or work interference
- Awareness of benefits and anonymity strongly influence help-seeking behavior
- Older age groups show a higher **percentage** of treatment despite lower counts

---

## ✅ Tools Used
- Python (Pandas, Matplotlib, Seaborn)
- Jupyter Notebook
- VS Code
