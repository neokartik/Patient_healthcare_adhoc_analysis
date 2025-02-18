# Healthcare Database Analysis - SQL Queries & Insights

This project involves SQL-based analysis of a **Healthcare Database**, offering comprehensive insights into patient demographics, medical conditions, treatments, financial aspects, and hospital performance. The findings contribute to informed decision-making and improved healthcare management.

---

## 1. Data Overview & Basic Statistics
- Explored patient records to gather a comprehensive view of healthcare data.
- Counted total records, analyzed maximum and average ages of hospitalized patients.
- Demographic analysis based on age distribution.

## 2. Medical Conditions & Medications
- Identified **prevalent medical conditions** and the most frequently prescribed medications.
- Analyzed the distribution of medical conditions within the dataset.

## 3. Insurance Providers & Hospitals
- Evaluated **patient preferences** for insurance providers and hospitals.
- Insights aid in **resource allocation** and understanding coverage preferences.

## 4. Financial Analysis & Hospitalization Duration
- Examined **average billing amounts** across different medical conditions.
- Analyzed **hospital efficiency** and the duration of patient stays.

## 5. Blood Type Analysis & Donation Matching
- Studied **blood type distribution** and potential correlations with age groups.
- Created a stored procedure **'Blood_Matcher'** to match donors and recipients based on:
  - Blood type
  - Age

## 6. Yearly Admissions & Insurance Analysis
- Analyzed hospital admissions for **2024** and **2025**.
- Identified trends in billing patterns across various **insurance providers**.

## 7. Patient Risk Categorization
- Categorized patients into **High**, **Medium**, and **Low-risk** groups.
- Classification based on **medical conditions** and **test results**.

---

## Database Schema

| **Column**         | **Description**                                                                 |
|---------------------|---------------------------------------------------------------------------------|
| `Name`              | Patient name.                                                                  |
| `Age`               | Age of patient at admission.                                                   |
| `Gender`            | Gender of patient. (`Male`/`Female`)                                            |
| `Blood Type`        | Blood group. (`A+`, `O-`, `B-`, etc.)                                            |
| `Medical Condition` | Primary diagnosis (e.g., `Diabetes`, `Asthma`).                                  |
| `Date of Admission` | Date of hospital admission.                                                      |
| `Doctor`            | Name of the attending doctor.                                                   |
| `Hospital`          | Hospital name where the patient was admitted.                                   |
| `Insurance Provider`| Patient's insurance provider.                                                    |
| `Billing Amount`    | Billed amount for the patient's treatment.                                       |
| `Room Number`       | Room number assigned during admission.                                           |
| `Admission Type`    | Type of admission (`Emergency`, `Elective`, `Urgent`).                           |
| `Discharge Date`    | Date when the patient was discharged.                                            |
| `Medication`        | Medication prescribed (e.g., `Aspirin`, `Penicillin`).                          |
| `Test Results`      | Outcome of tests: (`Normal`, `Abnormal`, `Inconclusive`).                        |

---


**Author**: Kartik Raghuwanshi 
**Project**: Healthcare Database Analysis  
**Technologies**: SQL, MySQL ,Excel, Data Analysis  

*Happy Querying! 🚀*
