![Dashboard Preview](Screenshots/dashboard.png)

🏥 Hospital Emergency Room Analytics Dashboard (Excel + Power Query)

This project presents a real-world style Emergency Room (ER) analytics dashboard, designed using Microsoft Excel, Power Query, and Power Pivot.
The goal is to transform raw CSV patient data into actionable insights that support hospital decision-making and resource planning.

📊 Dashboard Highlights
Insight Area	Description
🏥 Admission Status	Compare the number of patients admitted vs. not admitted
📍 Department Referrals	Identify the most frequently referred specialties like Orthopedics, General Practice, Gastroenterology, etc.
👦👩 Gender Analysis	Analyze patient visit volume by gender
⏱ Timeliness of Care	Measure % of patients attended within 30 minutes
👶👵 Patient Age Distribution	Group patients by age category to understand ER patient demographics
🛠 Tech Stack & Tools Used
Tool	Purpose
Microsoft Excel	Visual dashboard creation
Power Query	Data cleaning, transformation, time conversion, merging columns
Power Pivot	Data modeling and DAX calculations
Pivot Tables & Charts	KPI cards, Measures, Visualizations
Slicers & Buttons	Interactive month/year filter controls
🧹 Data Cleaning & Transformation (Power Query)

Removed duplicate values

Converted text timestamps to valid datetime format

Split & merged columns for proper data model structure

Replaced inconsistent values in patient status fields

Created clean data model table ready for pivot usage

📈 Dashboard KPIs
KPI	Description
Total ER Visits	Count of patient rows
Avg. Wait Time	Mean patient wait duration
Satisfaction Score	Average satisfaction rating
On-Time Attendance Rate	% of patients seen within 30 minutes
📎 Repository Structure
📁 Hospital-ER-Dashboard/
│
├── 📂 Data/                # Raw & Cleaned CSV files
├── 📊 Dashboard.xlsx       # Final Excel Dashboard
├── 📝 README.md            # Project Documentation
└── 📁 Snapshots/           # Dashboard Images

🚀 Future Improvements

Predictive model for expected wait time

Power BI version of dashboard

Automated daily email report generation

Dynamic forecasting using DAX measures

🤝 Contributions

Pull Requests are welcome!
If you’d like to collaborate on healthcare analytics tools, feel free to fork and improve the project.

👨‍💻 Author

MWK — Data Analyst & Dashboard Developer
📌 Skills: Excel | Power Query | Power Pivot | Data Cleaning | Business Reporting
