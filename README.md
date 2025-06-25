 # Drug Safety and Pharma Analytics Project

This project explores real-world pharmacovigilance data from the FDA Adverse Event Reporting System (FAERS) to identify patterns in adverse drug events (ADEs), detect safety signals, and build a foundation for risk profiling of drugs. It is intended as a proof-of-concept for leveraging public healthcare data to support regulatory, R&D, and clinical safety efforts.

---

## 🚀 Project Objective

- Analyze adverse event reports submitted to the FDA.
- Identify high-risk drugs, outcomes, and demographic trends.
- Apply statistical methods to detect significant safety signals.
- Demonstrate how clustering and classification can aid in drug profiling and monitoring.

---

## 📁 Dataset

- **Source**: [FAERS (FDA Adverse Event Reporting System)](https://www.fda.gov/drugs/questions-and-answers-fdas-adverse-event-reporting-system-faers/fda-adverse-event-reporting-system-faers-public-dashboard)
- **Format**: Quarterly data files in `.txt` format (converted to `.csv`)
- **Scope**: Over 10 million reports spanning drugs, reactions, patient demographics, and outcomes.

---

## 🛠️ Tech Stack

- **Language**: Python
- **Environment**: Jupyter Notebook / Python 3.x

### 🔧 Libraries Used

- `Pandas` – Data cleaning and manipulation  
- `Matplotlib` / `Seaborn` – Data visualization  
- `Statsmodels` – Statistical modeling and hypothesis testing  
- `Scikit-learn` – Clustering and classification models  
- `NumPy` – Numerical operations

---

## 📊 Key Analyses

### 1. **Data Cleaning & Preprocessing**
- Merging FAERS files
- Handling duplicates and missing values
- Standardizing drug and reaction names

### 2. **Exploratory Data Analysis (EDA)**
- Frequency distribution of ADEs by drug and system organ class
- Trends over time and across demographics
- Heatmaps and bar charts for visual insights

### 3. **Signal Detection**
- Disproportionality analysis (PRR/ROR)
- Logistic regression to estimate severity likelihood
- Statistical significance testing (p-values, confidence intervals)

### 4. **Advanced Modeling**
- Clustering drugs based on reaction profiles
- Predicting severe outcomes using classification models

---

## 📈 Outcomes

- Identified drug-reaction pairs with disproportionate reporting
- Highlighted demographic trends in ADEs (age, gender)
- Demonstrated feasibility of using machine learning for early signal detection
- Developed reproducible analysis pipeline and visual reports

---


