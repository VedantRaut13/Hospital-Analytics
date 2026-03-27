# Hospital-Analytics

Business Case:

The objective of this project was to analyze healthcare operational data comprising 120K visits, 20K patients, and $76M in revenue to support strategic decision-making across hospitals.

The analysis aimed to answer key business questions:

Which hospitals and specialties experience the highest patient demand?
Which doctors contribute most to workload and revenue?
Which diagnoses are most common and most financially impactful?
Which patient groups drive healthcare utilization?

The goal was to transform raw healthcare data into an interactive Power BI dashboard that enables hospital management to optimize resource allocation, improve patient care, and enhance revenue performance.

Analytical Approach

Data Modeling
Designed a structured STAR Schema model linking:
Hospitals.
Doctors.
Patients.
Time dimensions.
Visits.

Data Preparation (ETL)
Cleaned and transformed healthcare data using Power Query to replace null values, clean and Trim text, change Data types and other transformations.

KPI Development (DAX)

Developed key healthcare KPIs:

Total Visits: 120K.
Total Revenue: $76M.
Revenue per Visit: $636.
Average Treatment Cost: $4K.

Dashboard Design

Built 3 interactive views:

Executive View → Overall hospital performance.
Doctor View → Performance & workload.
Patient & Diagnosis View → Trends & demographics.

Key Insights

Orthopedics and Endocrinology generate the highest patient visits among specialties.
Certain hospitals (e.g., Dublin South Care Hospital) lead in total visits.
Top-performing doctors (e.g., Sandra Hill) handle the highest workload and revenue contribution.
Hypertension and Diabetes are the most common diagnoses.
High-revenue diagnoses include hypertension and post-operative follow-ups.
Patients aged 65+ contribute the highest healthcare demand.

Impact & Business Value

Enabled hospitals to allocate staff based on high-demand specialties.
Identified top-performing doctors for workload balancing.
Highlighted high-revenue diagnoses for strategic focus.
Improved patient segmentation for targeted healthcare services.
Provided a centralized dashboard for real-time decision-making.
Established a scalable analytics framework for multi-hospital systems.
