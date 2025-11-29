# HR-Dashboard
### 1. Project Title

👥HR Analytics Dashboard: Awesome Chocolates
A Power BI dashboard that provides a complete overview of employee distribution, salary trends, age groups, and leave balances.

### 2. Short Description / Purpose

This dashboard gives HR teams a clear picture of the workforce. It helps understand employee demographics, job roles, salary patterns, and growth over time. It also highlights which departments have higher leave balances and which roles are most common.

### 3. Tech Stack
   
The dashboard was built using the following tools and technologies:<br>
• 📊 Power BI Desktop – Main data visualization platform used for report creation.<br>
• 📂 Power Query – Data transformation and cleaning layer for reshaping and preparing the HR data.<br>
• 🧠 DAX (Data Analysis Expressions) – Used for calculated measures(Totals, averages, percentages) dynamic visuals and conditional logic.<br>
• 📝 Data Modeling – Linking employee tables for better filtering.<br>
• 📁 File Format – .twbx for development and .png for dashboard previews.

### 4. Data Source

Dataset sourced from publicly available internal HR employee records. (Kaggle/UCI Repository).
Contains employee details such as:

• Job titles<br>
• Gender information<br>
• Age and age groups<br>
• Educationa Qualifications<br>
• Salary details<br>
• Leave balance data<br>
• Year of joining

Data preparation included age grouping, identifying top earners, cleaning missing values, and creating measures for salary and leave insights.

### 5. Features and Highlights

### Business Problem

Healthcare teams often lack an easy way to interpret survival trends and risk factors from raw clinical data. Identifying which age groups or health conditions contribute to higher mortality is critical.

### Goal of the Dashboard

• To provide a visual analytical tool that highlights:<br>
• Survival trends across age categories<br>
• Influence of serum sodium levels on survival<br>
• Impact of diabetes on patient outcomes<br>
• Gender-based differences in survival<br>
The dashboard supports early detection strategies and risk-based patient monitoring.

### Key Visuals Explained

### • KPI Cards

• Alive Percentage<br>
• Average Alive Value<br>
• Total Alive<br>
• Total Death<br>
These metrics give an overall snapshot of patient outcomes.

### • Total Alive by Category

A bar and line chart displaying how many patients are alive across different age segments. Shows highest survival in the 51–60 group and lowest in 71+.

### • Average Serum Sodium by Age Group

A combined bar and line visual comparing the average serum sodium levels across age groups and its relation to survival outcomes.

### • Total Alive by Age Group

A line/area chart illustrating survival distribution. Shows a clear decline in survival as age increases.

### • Total Alive vs Diabetes Count

A stacked chart indicating how the presence of diabetes impacts survival in each age segment.

### • Gender Slicer

Interactive buttons to filter the dashboard by male or female patients for targeted analysis.

### 6. Business Impact and Insights

• Survival probability decreases significantly in patients aged 71+.<br>
• Serum sodium levels are strongly correlated with survival outcomes.<br>
• Diabetes is a prominent risk factor in the 51–70 age groups.<br>
• Gender filtering reveals differences in survival distribution and risk levels.<br>
• Supports clinicians and researchers in making early diagnosis and targeted interventions.


### 7. Screenshot
![Dashboard Preview](https://github.com/adapakavya/Heart-disease-Dashboard/blob/main/heart_disease.png)

