# Healthcare-Analytics-Dashboard

## 📊 Project Overview
An executive-grade interactive Power BI dashboard analyzing 55.5K patient admissions across clinical quality, financial performance, and demographics.

## 🗃️ Dataset
Downloaded a .csv file of healthcare_dataset from kaggle.

## 💡 Key Insights
* **Financial Driver:** **Endocrinology** leads hospital revenue, generating **$239M** in total billings.
* **Payer Leader:** **Cigna** represents the highest-value commercial contract at **$287.14M**.
* **Primary Demographic:** Senior citizens aged **66+** form the dominant patient cohort.
* **Bed Bottleneck:** **Asthma** patients experience the longest average hospital stay at **15.7 days**.

## 🎯 Strategic Recommendations
* **Resource Planning:** Allocate additional resources and staffing to departments with the highest billing and patient demand, particularly Endocrinology.
* **Senior Patient Care:** Develop targeted care programs for patients aged 66+ since they represent the largest patient group.
* **Clinical Efficiency:** Investigate factors contributing to longer stays among Asthma patients to identify opportunities for reducing hospitalization duration.
* **Performance Monitoring:** Continue monitoring revenue and admission trends annually to identify emerging changes in patient demand and departmental performance.
* **Data Reporting:** Separate full-year and partial-year reporting periods to ensure accurate year-over-year performance comparisons.

## 🛠️ Tech Stack & DAX Methods
* **Data Modeling:** Star Schema (`fact_table` linked to `medics_table`, `patient_table` and `calendar_table`).
* **Time Intelligence:** Used `SAMEPERIODLASTYEAR` to compute Year-over-Year (YoY) revenue growth rates.
* **Context Manipulation:** Utilized `CALCULATE` and `DIVIDE` to isolate patient demographic distributions safely.
* **UI/UX Design:** Custom vertical sidebar navigation utilizing native Page Navigators with interactive Hover/Pressed visual states.

## 📂 How to View
* Download the 'Healthcare-Data-Analytics.pbix' file from this repository.
* Open in Power BI Desktop.
* To land on different report `ctrl + press` that perticular report.
* Interact with the Year Slicer to see how metrics shift over time.
