# osa-cardiovascular-readmissions-ebm
Healthcare Data Analytics project optimizing 30-day readmissions and ALOS in OSA cohorts using ICD-10 and HL7 FHIR standards.
# 🩺 Optimization of Cardiovascular Risk & Hospital Readmissions in Obstructive Sleep Apnea (OSA) Cohorts

## 📊 1. Executive Summary & Business Problem (Avery Smith Strategy)
- **The Question:** How can integrated Lifestyle Medicine interventions reduce the 30-day hospital readmission rate and shorten the Average Length of Stay (ALOS) for patients suffering from severe Obstructive Sleep Apnea (OSA)?
- **Business Impact:** 30-day hospital readmissions generate massive financial losses for healthcare facilities due to payer penalties (e.g., HRRP program) and bed confinement. This project aims to prove that targeted behavioral care for patients at the highest cardiovascular risk brings real budget savings and healthcare quality improvement.

## 🧬 2. Healthcare Domain, Metrics & Standards (Josh Matlock Blueprint)
This project utilizes core clinical concepts, hospital metrics, and international health data standards:
- **Clinical Coding:** Identification of the patient cohort based on the **ICD-10-CM** classification (Primary Code: `G47.33` - Obstructive Sleep Apnea).
- **Core Metrics:** 
  - *30-Day Readmission Rate* – The percentage of patients readmitted to the hospital within 30 days of discharge.
  - *ALOS (Average Length of Stay)* – The average number of days a patient spends in the hospital.
  - *AHI (Apnea-Hypopnea Index)* – The clinical index of sleep apnea severity derived from polysomnography.
- **Data Interoperability:** The source database design reflects resource mapping within the modern **HL7 FHIR** standard:
  - `Patient` (demographics and anthropometric parameters: BMI, age).
  - `Observation` (polysomnography results and clinical laboratory markers).
  - `Encounter` (hospitalization timeline and structural details).

## 🗄️ 3. SQL Data Extraction & Clean-Up (Alex The Analyst Method)
*The following SQL query is designed to extract and clean the target research cohort from the relational EHR database (modeling National Sleep Research Resource structures - sleepdata.org).*

```sql
-- [STATUS: IN PROGRESS - LEARNING VIA ANALYST BUILDER]
-- The custom SQL code (SELECT, WHERE, JOIN, GROUP BY) will be implemented here
-- as soon as the corresponding data manipulation modules are completed.
```

## 📉 4. Evidence-Based Medicine (EBM) Statistical Results
*Statistical analysis conducted based on the "Medical Statistics at a Glance" methodology (UQ Clinical Epidemiology Focus).*
- Calculation of Odds Ratio (OR) for hospital readmission based on the correlation of BMI parameters and AHI scores.
- Verification of statistical significance using *p-values* (p < 0.05) and 95% Confidence Intervals (95% CI).

## 📊 5. Interactive Dashboard
*Link to the fully interactive, business-focused dashboard verifying the research hypotheses:*
👉 [View my interactive dashboard on Maven Analytics Showcase](LINK_WILL_BE_ADDED_HERE)

