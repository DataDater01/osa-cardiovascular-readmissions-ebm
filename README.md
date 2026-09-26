# osa-cardiovascular-readmissions-ebm
Healthcare Data Analytics project optimizing 30-day readmissions and ALOS in OSA cohorts using ICD-10 and HL7 FHIR standards.
# 🩺 Optimization of Cardiovascular Risk & Hospital Readmissions in Obstructive Sleep Apnea (OSA) Cohorts

## 📊 1. Executive Summary & Business Problem (Avery Smith Strategy)
- **The Question:** Jak zintegrowane interwencje z zakresu Medycyny Stylu Życia (Lifestyle Medicine) mogą zmniejszyć wskaźnik ponownych hospitalizacji (30-Day Readmission Rate) oraz skrócić średni czas pobytu (ALOS) pacjentów cierpiących na ciężką postać obturacyjnego bezdechu sennego (OSA)?
- **Business Impact:** Ponowne hospitalizacje w ciągu 30 dni od wypisu (Readmissions) generują gigantyczne straty finansowe dla placówek medycznych ze względu na kary nakładane przez płatników (np. program HRRP) oraz blokowanie łóżek szpitalnych. Ten projekt ma na celu udowodnienie, że ukierunkowana opieka behawioralna nad pacjentami o najwyższym ryzyku sercowo-naczyniowym przynosi realne oszczędności budżetowe i poprawę jakości opieki (Healthcare Quality Improvement).

## 🧬 2. Healthcare Domain, Metrics & Standards (Josh Matlock Blueprint)
W projekcie wykorzystano kluczowe koncepcje, metryki szpitalne oraz międzynarodowe standardy danych medycznych:
- **Clinical Coding:** Identyfikacja kohorty pacjentów w oparciu o klasyfikację **ICD-10-CM** (kod główny: `G47.33` - Obstructive Sleep Apnea).
- **Core Metrics:** 
  - *30-Day Readmission Rate* – Wskaźnik ponownych przyjęć na oddział w ciągu 30 dni od wypisu.
  - *ALOS (Average Length of Stay)* – Średni czas pobytu pacjenta na oddziale (zajętość łóżka).
  - *AHI (Apnea-Hypopnea Index)* – Kliniczny wskaźnik ciężkości bezdechu uzyskany z polisomnografii.
- **Data Interoperability:** Struktura źródłowa projektu odzwierciedla mapowanie zasobów w nowoczesnym standardzie **HL7 FHIR**:
  - `Patient` (demografia i parametry antropometryczne: BMI, wiek).
  - `Observation` (wyniki badań polisomnograficznych oraz markerów laboratoryjnych).
  - `Encounter` (dane dotyczące przebiegu i czasu trwania hospitalizacji).

## 🗄️ 3. SQL Data Extraction & Clean-Up (Alex The Analyst Method)
*Poniższe zapytanie SQL zostało zaprojektowane w celu wyekstrahowania i oczyszczenia docelowej kohorty badawczej z relacyjnej bazy danych repozytorium EHR (na wzór struktur National Sleep Research Resource - sleepdata.org).*

```sql
-- [STATUS: W TRAKCIE NAUKI W ANALYST BUILDER]
-- Tutaj wkleję mój autorski kod SQL (SELECT, WHERE, JOIN, GROUP BY), 
-- gdy tylko opanuję odpowiednie moduły na platformie.
```

## 📉 4. Evidence-Based Medicine (EBM) Statistical Results
*Analiza biostatystyczna przeprowadzona w oparciu o metodologię "Medical Statistics at a Glance" (UQ Clinical Epidemiology Focus).*
- Wyznaczenie Ilorazu Szans (Odds Ratio) dla wystąpienia ponownej hospitalizacji w zależności od korelacji parametrów BMI oraz wskaźnika AHI.
- Weryfikacja istotności statystycznej uzyskanych wyników za pomocą wartości *p-value* (p < 0.05) oraz 95% przedziałów ufności (95% CI).

## 📊 5. Interactive Dashboard
*Link do w pełni interaktywnego, biznesowego dashboardu weryfikującego hipotezy badawcze:*
👉 [Zobacz mój interaktywny dashboard na platformie Maven Analytics Showcase](W_PRZYSZLOSCI_WKLEISZ_TUTAJ_LINK)
