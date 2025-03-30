# 🏥 SQL Data Analysis – Healthcare Dataset  
![SQL](https://img.shields.io/badge/Language-SQL-yellow?style=flat-square)  
![Workbench](https://img.shields.io/badge/Workbench-MySQL-green?style=flat-square)  


## 🔍 Project Overview
This project simulates a real-world healthcare data analysis for Apollo Hospital, similar to work done at Kantar. Using SQL, we analyzed patient demographics, medical conditions, treatments, and hospital performance to optimize resource allocation and improve patient care.
---

## 📊 Key Analyses & Insights  

### 1️⃣ **Patient Demographics & Statistics**  
- Explored total records, max & average patient age, and age-based demographic distribution.  

### 2️⃣ **Medical Conditions & Medications**  
- Identified common health conditions, prescribed medications, and their frequency to assess treatment patterns.  

### 3️⃣ **Hospital & Insurance Trends**  
- Analyzed patient preferences for hospitals and insurance providers, helping in resource planning and policy optimization.  

### 4️⃣ **Financial Analysis & Hospitalization Trends**  
- Assessed average billing amounts, total hospital revenue, and patient hospitalization duration across facilities.  

### 5️⃣ **Blood Type Analysis & Donation Matching**  
- Mapped blood type distribution by age group and developed a stored procedure (`Blood_Matcher`) to match potential donors and recipients.  

### 6️⃣ **Yearly Admissions & Insurance Analysis**  
- Tracked patient admissions for 2024-2025 and examined insurance-based billing disparities.  

### 7️⃣ **Patient Risk Categorization**  
- Implemented a classification system (High, Medium, Low) based on medical conditions and test results for quick risk assessment.  

---

## 🏷️ Dataset Columns & Descriptions  

| Column Name           | Description |
|-----------------------|------------|
| **Name**             | Patient's full name |
| **Age**              | Age at the time of admission |
| **Gender**           | "Male" or "Female" |
| **Blood Type**       | Patient's blood group (e.g., A+, O−, etc.) |
| **Medical Condition**| Primary diagnosis (e.g., Diabetes, Hypertension) |
| **Date of Admission**| Patient’s hospital admission date |
| **Doctor**           | Treating physician's name |
| **Hospital**         | Facility where the patient was admitted |
| **Insurance Provider** | Insurance company covering the patient |
| **Billing Amount**   | Total medical bill (currency value) |
| **Room Number**      | Patient’s assigned hospital room |
| **Admission Type**   | Emergency, Elective, or Urgent admission |
| **Discharge Date**   | Date of patient discharge |
| **Medication**       | Prescribed drugs (e.g., Aspirin, Paracetamol) |
| **Test Results**     | Medical test outcomes – Normal, Abnormal, or Inconclusive |

---

## 🛠️ Tools & Technologies Used  
- **SQL (MySQL Workbench)** – Data extraction & query optimization  
- **Stored Procedures** – Automating donor-patient matching  
- **Data Aggregation & Grouping** – Statistical insights  
- **Joins & Subqueries** – Complex data relationships  

📌 **Check out the full SQL queries & analysis in the repository!**  
