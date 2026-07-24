# PowerBI_Professional_Survey_Breakdown

A single-page Power BI dashboard that visualizes results from a survey of data professionals, covering roles, compensation, tools, geography, and job satisfaction.

---Overview---

The report is built on a single table, Data Professional Survey, where each row represents one survey respondent. The dashboard surfaces high-level KPIs alongside breakdowns by role, language, country, and satisfaction — designed as a one-screen summary rather than a multi-page drill-down report.

---Dashboard Contents---

KPI Cards

People Surveyed — count of respondents (Unique ID)
Average Age — mean respondent age (Q10 - Current Age)

---Charts---

Average Salary by Job Title (Bar chart) — mean salary broken out by current role (Q1)
Favorite Programming Languages (Column chart) — count of respondents by favorite language (Q5), broken out by job title
Country of Survey Takers (Treemap) — respondent count by country (Q11)
Happiness with Salary (Gauge) — average satisfaction score for salary (Q6)
Happiness with Work-Life Balance (Gauge) — average satisfaction score for work-life balance (Q6)
Average Salary by Sex (Donut chart) — salary breakdown by respondent sex
How Difficult to Break Into Data (Donut chart) — distribution of responses on career-entry difficulty (Q7)

---Data Source---

Survey responses covering questions on job title, salary, programming language preference, location, age, career-entry difficulty, and satisfaction with salary and work-life balance. Each survey question is stored as its own column (e.g. Q1 - Which Title Best Fits your Current Role?, Q5 - Favorite Programming Language, Q6 - How Happy are you in your Current Position with the following? (Salary)).

---Tools Used---

Power BI Desktop

How to Use
Open Data_Professional_Survey_Breakdown.pbix in Power BI Desktop.
Refresh the data connection if prompted (Home → Refresh).
Explore the dashboard — cross-filtering is enabled, so clicking any chart segment (e.g. a job title or country) filters the rest of the visuals accordingly.


---Key Takeaways---

Salary varies notably by job title, offering a quick view of compensation across data roles.
Programming language preference differs by role, useful for understanding tooling trends across the field.
Respondents skew toward a handful of countries, visualized via the treemap's proportional sizing.
Satisfaction gauges make it easy to compare how respondents feel about pay versus work-life balance at a glance.

-side note
This data set could have been cleaned more extensively.
Programming language preference differs by role, useful for understanding tooling trends across the field.
Respondents skew toward a handful of countries, visualized via the treemap's proportional sizing.
Satisfaction gauges make it easy to compare how respondents feel about pay versus work-life balance at a glance.
