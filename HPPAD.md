📌 #Project Overview
The IFEXA Healthcare Analytics Dashboard is a Power BI business intelligence project that provides a consolidated view of healthcare operations, patient characteristics, financial performance, and patient experience.
The completed report contains five major analytical areas:
1.	Executive Overview
2.	Patient Analysis
3.	Hospital Operations
4.	Financial Performance
5.	Patient Experience
The report also includes interactive filtering, Drill-through analysis, and a detailed department or branch view.
🎯 Project Objectives
The dashboard was developed to:
•	Monitor overall healthcare performance.
•	Understand patient demographics and healthcare utilization.
•	Identify high-performing departments and services.
•	Analyse revenue, cost, profit, and financial targets.
•	Evaluate patient waiting time and satisfaction.
•	Examine patient outcomes.
•	Compare performance across states and branches.
•	Identify operational and financial areas requiring further investigation.

**📊 Dashboard Pages**
**1. 🏠 Executive Overview**
Provides a high-level summary of healthcare and financial performance.
KPI	Result
Total Revenue	$47.84M
Total Patients	1K
Total Visits	2.92K
Average Revenue per Patient	$39.87K
Average Waiting Time	45.27
Average Satisfaction Score	3.71
Total Cost	$29.50M
Total Profit	$18.35M
The report records approximately 2,920 visits from 1,000 patients, generating $47.84M in revenue and $18.35M in profit. 

**2. 👥 Patient Analysis**
This page analyses patient characteristics, distribution, and utilization patterns.
Analysis areas:
•	Patients by Age Group
•	Patients by Gender
•	Patients by Diagnosis
•	Patients by State
•	New vs Returning Patients
•	Average Visits per Patient
•	Patient Outcomes
Key findings:
•	The 31–40 age group is the most prominent.
•	Malaria is the most prevalent recorded diagnosis.
•	Rivers has the highest number of patient records among the four states.
•	Average visits per patient are 2.43.
•	Patient outcomes include Recovered, Follow-up, Admitted, and Referred.
•	649 patients are recorded as recovered. 

**3. 🏥 Hospital Operations**
This page evaluates operational efficiency and service delivery.
Analysis areas:
•	Visits by Department
•	Waiting Time by Department
•	Patient Satisfaction by Department
•	Patient Outcomes
•	Branch Performance
•	Monthly Patient Volume
Key findings:
•	Pediatrics records the highest department visit volume, with 10,247 visits.
•	Overall average waiting time is 45.27.
•	Pediatrics records the strongest patient satisfaction among the departments shown.
•	Branch-level performance is compared across patient activity, cost, profit, revenue, and waiting time.
•	August is identified as the highest-volume month.

**4. 💰 Financial Performance**
This page examines how patient activity translates into financial performance.
Analysis areas:
•	Revenue by Service
•	Revenue by State
•	Revenue by Department
•	Profit by Department
•	Monthly Revenue
•	Revenue Target vs Total Revenue
•	Revenue Variance
•	Achievement %
•	Profit Margin
•	Average Revenue per Patient
KPI	Result
Total Revenue	$47.84M
Total Cost	$29.50M
Total Profit	$18.35M
Profit Margin	38%
Revenue Target	$200M
Revenue Variance	-$152.16M
Achievement	24%
Average Revenue per Patient	$39.87K
Key findings:
•	Rivers leads state-level revenue generation at approximately $12.73M.
•	Pediatrics is the highest-performing department, generating approximately $9.39M.
•	Pediatric Care is the strongest revenue-generating service.
•	There is a substantial gap between revenue target and actual revenue.
•	Pharmacy performance is identified as an area requiring further financial investigation. 

**5. ❤️ Patient Experience**
This page evaluates patient experience using satisfaction, waiting time, outcomes, and service-location comparisons.
Analysis areas:
•	Average Satisfaction Score
•	Satisfaction by Department
•	Satisfaction by Branch
•	Satisfaction vs Waiting Time
•	Patient Outcomes
•	Satisfaction Distribution
KPI	Result
Average Satisfaction Score	3.71
Average Waiting Time	45.27
Positive Outcomes	649
Positive Outcome Rate	54.1%
Total Patients	1K
Key findings:
•	Overall average satisfaction score is 3.71.
•	Pharmacy records the highest department satisfaction in the report, while Maternity records the lowest.
•	Nnewi records an average satisfaction score of 3.88, above the overall average.
•	The report indicates that shorter waiting time does not necessarily correspond to higher satisfaction across the branches and departments reviewed.
•	Satisfaction score 5 has the highest number of patients in the reported distribution. 

**🔍 Executive Insights**
🌍 Geographic Performance
Rivers leads in revenue generation and records the highest patient activity among the states shown.
🏥 Department Performance
Pediatrics is a major operational and financial contributor, recording the highest visit volume and departmental revenue.
💰 Financial Performance
The organization generated $47.84M in revenue against a $200M target, producing a reported 24% achievement level and -$152.16M variance.
❤️ Patient Experience
Overall satisfaction stands at 3.71, while 54.1% of patients are classified as having positive outcomes.
⏱️ Operational Efficiency
Overall average waiting time is 45.27, with differences across departments and branches. 

**🛠️ Tools & Technologies**
•	Microsoft Power BI
•	DAX
•	Microsoft Excel
•	Data Modelling
•	Data Cleaning & Transformation
•	Interactive Data Visualization
•	KPI Development
•	Drill-through Analysis
•	Report Page Tooltips

**🔄 Interactive Features**
The report incorporates:
•	Page navigation
•	Slicers for Date, State, Branch, Department, and Gender
•	Drillthrough pages for detailed department analysis
•	Branch and state-level analysis
•	Report-page tooltips
•	Dynamic KPI cards
•	Cross-filtering between visuals
The report includes a Department Details Drill-through page with metrics such as total patients, visits, waiting time, satisfaction, monthly visits, outcomes, revenue, and positive outcome percentage. 
**📐 Example DAX Measures**
Total Patients =
DISTINCTCOUNT(Patient_Visits[Patient_ID])
Total Revenue =
SUM(Patient_Visits[Revenue_NGN])
Total Cost =
SUM(Patient_Visits[Cost_NGN])
Total Profit =
[Total Revenue] - [Total Cost]
Average Revenue Per Patient =
DIVIDE([Total Revenue], [Total Patients], 0)
Average Waiting Time =
AVERAGE(Patient_Visits[Waiting_Time])
Average Satisfaction Score =
AVERAGE(Patient_Visits[Satisfaction_Score])
Positive Outcome % =
DIVIDE([Positive Outcomes], [Total Patients], 0)

📁 Suggested Repository Structure
IFEXA-Healthcare-BI/
│
├── README.md
├── IFEXA_Healthcare_Dashboard.pbix
├──finalproject.pdf
└── 📸screenshots/
    ├── executive-overview.png
    ├── patient-analysis.png
    ├── hospital-operations.png
    ├── financial-performance.png
    └── patient-experience.png

💡 **Business Value**
The dashboard connects:
Patients → Services → Operations → Revenue → Outcomes → Experience
It provides a unified decision-support environment for identifying high-performing areas, monitoring operational efficiency, evaluating patient experience, and recognizing financial performance gaps.

👨‍💻 **Author**
Adewale Elijah Adejumo
Healthcare | Microbiology | Data Analytics | Power BI
Turning healthcare data into actionable insights through analytics, visualization, and evidence-based decision-making.

⭐ **Project Takeaway**
The IFEXA Healthcare Analytics Dashboard demonstrates the practical application of Power BI, DAX, data modelling, KPI development, interactive visualization, Drill-through, and report-page tooltips to a healthcare business intelligence problem.
The project moves beyond simply reporting numbers by connecting patient behaviour, operational efficiency, financial performance, and patient experience into a unified decision-support dashboard.

