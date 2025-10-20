DataCamp Portfolio Projects

This repository contains SQL-based projects completed as part of DataCamp's guided curriculum. The goal is to demonstrate proficiency in querying, aggregating, and analyzing data using PostgreSQL/SQL.

---

1. Project: Analyzing Students' Mental Health

Objective
This project explores whether the **'length of stay'** impacts the average mental health diagnostic scores of international students using PostgreSQL.

Data
The dataset comes from a study conducted at a Japanese international university in 2018. The goal was to analyze how international students' mental health (depression, social connectedness, acculturative stress) changes based on how long they have stayed in Japan.

Key Metrics Calculated
The final query groups the results by `stay` (length of stay) and calculates the average scores for several mental health indicators:

| Column Name | Description |
| :--- | :--- |
| `count_int` | Count of international students for each length of stay. |
| `average_phq` | Average PHQ (Patient Health Questionnaire) score. |
| `average_scs` | Average Social Connectedness Scale score. |
| `average_as` | Average Acculturative Stress score. |

---

2. Project: Analyze International Debt Statistics

Objective
This project analyzes a dataset containing information about the debt statistics of various countries, focusing on calculating total debt and finding countries with the highest/lowest principal repayments.

Data
The dataset contains columns like `country_name`, `indicator_code`, and `debt` (in current US dollars).

Key Findings
1. **Total Distinct Countries:** The database contains debt records for **124** distinct countries.
2. **Country with Highest Total Debt:** **China** has the highest total debt ($\approx$ $285,793,494,734.2$).
3. **Country with Lowest Principal Repayment:** **Timor-Leste** has the lowest recorded principal repayment for the indicator code `DT.AMT.DLXF.CD` ($\$825,000$).