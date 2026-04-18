# HR Performance & Salary Analytics Dashboard

## 📊 Dashboard Preview
![Dashboard Preview](Excel_Dashboard.png) 

## 🎯 The Story of the Project
The goal of this project was to consolidate scattered HR data and present it in a clear, concise story about branch performance and salary trends. I wanted to answer a simple question: *Where is our investment in people showing the best results?*

## 🛠️ Step-by-Step Transformation
Following a structured ETL process, I prepared the data for analysis:

1. **Consolidation:** I combined multiple data sources (Tabs) into one "Master Table" using Power Query to ensure a single version of the truth.
2. **Data Integrity:** I audited the data to fix formatting for dates and percentages, and used "Fill Down" logic to fix missing department names.
3. **Data Cleaning:** I manually resolved naming inconsistencies in city locations (like Cairo and Alexandria) to ensure the charts didn't show duplicate categories.
4. **KPI Design:** I built custom logic to calculate:
   * **Age & Tenure:** Measuring employee experience by years.
   * **Performance Benchmarking:** Creating an "Average Total %" to baseline success.
   * **Growth Analysis:** Calculating the "Delta" (the difference) in performance to see who is improving year-over-year.

## 💡 What the Data Told Me
* **Alexandria is thriving:** While it has the highest salary spend (47%), it also shows the strongest performance growth at 16%.
* **Education Matters:** There is a clear link between Bachelor's degrees (بكالوريوس) and higher performance scores.
* **Opportunity in Cairo:** The data suggests an opportunity to investigate why higher salaries in the Cairo branch haven't yet resulted in the same growth seen in other regions.

