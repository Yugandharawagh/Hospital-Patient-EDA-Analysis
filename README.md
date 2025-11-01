🏥 Hospital Patient Data EDA Project

Project Description 
Exploratory Data Analysis on hospital patient records to understand demographics, treatment trends, and billing patterns. Includes data cleaning, univariate &amp; bivariate analysis, time-based analysis, and correlation study with insightful visualizations.

🎯 Objective
The objective of this project is to perform a detailed Exploratory Data Analysis (EDA) on hospital patient records to understand patient demographics, treatment patterns, admission behavior, and billing trends.
The results help hospital management make informed decisions and improve patient care and operational efficiency.

📊 Dataset Overview
Details	Information
Total Records =	509
Total Features =	15
Data Type	= Tabular (CSV)
Domain =	Healthcare / Hospital Records

Columns
Patient_ID, Name, Age, Gender, Blood_Type, Disease,Admission_Date, Discharge_Date, Days_Admitted, Doctor,
Hospital_Department, Bill_Amount, Payment_Method, City, Follow_Up_Required

🧹 Data Cleaning & Preprocessing
Steps performed:
1) Removed duplicate entries
2) Filled/handled missing values
3) Corrected typo errors in categorical variables (Gender, Payment Method, Department)
4) Fixed invalid and inconsistent date formats
5) Ensured logical date order (Admission < Discharge)
6) Calculated Days_Admitted from date difference
7) Standardized text formatting and categories

   📈 Analysis Performed
✅ Univariate Analysis
Age distribution
Gender distribution
Department-wise admissions
Bill amount distribution

✅ Bivariate Analysis
Age vs Bill Amount
Department vs Average Stay Duration
Payment Method vs Bill Amount

✅ Time-Based Analysis
Monthly admission trends
Weekday vs Weekend admissions
Average stay length by department

✅ Correlation Analysis
Numerical variable correlation matrix
Correlation heatmap

📊 Visualizations
Visualization Type
Scatter Plot
Bar Plot
Line Chart
Heatmap
Correlation Heatmap

🛠️ Tech Stack
Tool / Library	Usage
Python	Data processing
Pandas, NumPy	Data cleaning & manipulation
Matplotlib, Seaborn	Visualization
Jupyter Notebook	Interactive development

📌 Key Insights & Findings
Insight	Interpretation
Older patients tend to have higher bills	Treatment cost increases with age
Cardiology patients stay the longest	Complex & critical treatments
Hospital admissions peak in winter	Seasonal illness patterns
Weekend admissions are lower	Elective cases mostly on weekdays
Bill amount correlates with duration of stay	Longer stay → higher cost

📂 Project Structure
📁 Hospital-Patient-EDA
 ├── 📁 data
 ├── 📁 notebooks
 ├── 📁 visuals
 ├── README.md
 └── requirements.txt

 ✅ Conclusion
This project provides insights into hospital patient patterns, billing behavior, and seasonal trends. It demonstrates how EDA helps healthcare organizations improve planning, patient handling, and cost management.

🚀 Future Enhancements
Machine learning model to predict bill amount or stay duration
Build a dashboard in Power BI/Tableau
Add real-time patient analytics pipeline

🤝 Contributions
Contributions, suggestions, and pull requests are welcome!

📬 Contact
For queries or suggestions, please create an issue on the repository.
