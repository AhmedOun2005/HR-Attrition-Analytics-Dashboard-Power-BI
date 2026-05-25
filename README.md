# HR Attrition Analytics Dashboard (Power BI)

## 📌 Project Overview
This interactive Power BI dashboard provides a deep-dive analysis into employee attrition. By analyzing key demographic, financial, and behavioral factors, this project uncovers the underlying drivers of employee turnover. The ultimate goal is to empower HR departments with data-driven insights to optimize retention strategies, improve workplace satisfaction, and reduce recruitment costs.

The project is structured into two main analytical perspectives:
1. **Overview Page:** High-level workforce demographics, departmental trends, and core KPIs.
2. **Details Page:** Deep dive into operational metrics, compensation structures, work-life balance, and employee satisfaction scores.

---

## 📊 Key Metrics & Insights

### 1. Workforce Demographics & Core KPIs
* **Total Headcount:** 1,470 active/historical employees.
* **Average Age:** ~37 years old, with a balanced distribution across different career stages.
* **Gender Distribution:** 60% Male (882 employees) and 40% Female (588 employees).
* **Marital Status:** Single employees represent a significant chunk of the workforce risk profile, alongside Married and Divorced segments.

### 2. Departmental & Role Attrition Triggers
* **High-Risk Departments:** **Research & Development** holds the largest share of total employees (~900+), followed by Sales. 
* **Critical Roles:** **Sales Executives**, **Research Scientists**, and **Laboratory Technicians** make up the bulk of the workforce, making attrition in these roles highly impactful to business continuity.
* **Education Fields:** Employees from **Life Sciences** and **Medical** backgrounds represent the majority of the staff.

### 3. Retention & Satisfaction Factors
* **Work-Life Balance:** A massive spike of over 890 employees rate their work-life balance at a moderate level (Level 3), indicating a critical area where subtle changes could sway retention.
* **OverTime:** The analysis tracks the correlation between heavy overtime work and potential burnout.
* **Job & Environment Satisfaction:** Tracks granular 1–4 satisfaction ratings across Job Role, Environment, and Relationships to pinpoint cultural or structural pain points.
* **Compensation & Growth:** Average monthly income sits at **$6.50K** with an average salary hike of **15.21%**. The dashboard tracks how these financial metrics correlate with tenure and time elapsed since the last promotion.

---

## 🛠️ Dashboard Architecture

### Page 1: Overview Page
Focuses on strategic macroeconomic HR KPIs to give executives an immediate health check of the organization.
* **KPI Cards:** Total Employees, Average Age, Average Salary Hike, Average Monthly Income, and Total Working Years.
* **Demographic Breakdowns:** Gender donut chart, Marital Status pie chart, and Education Field bar chart.
* **Operational Segments:** Business travel frequencies and Department/Job Role distributions.

### Page 2: Details Page
Designed for HR business partners to filter down into specific operational metrics and employee sentiment.
* **Advanced Slicers:** Interactive range sliders for **YearsAtCompany**, **YearsWithCurrManager**, **TotalWorkingYears**, **YearsInCurrentRole**, and **Education Level**.
* **Financial Gauges:** Radial gauges tracking Daily, Hourly, and Monthly financial rate averages.
* **Behavioral Analysis:** Overtime impact, Distance from Home area chart, Stock Option distributions, and Training frequency.
* **Satisfaction Matrix:** Comprehensive tabular view summarizing Job, Environment, and Relationship satisfaction count distributions.

---

## 🚀 Technical Features Implemented
* **Data Transformation & Cleaning:** Handled missing values, standardized categorical attributes, and optimized data types using **Power Query**.
* **Advanced DAX Modeling:** Formulated explicit measures for averages, percentages, and complex counts across multiple dimensions.
* **UX/UI Best Practices:** Implemented a clean, modern soft-gradient theme with a highly intuitive top-navigation toggle framework (`Overview Page` <-> `Details Page`).
* **Dynamic Slicing:** Enabled bidirectional cross-filtering to allow end-users to drill down into specific micro-segments of the employee population instantly.

---

## 📂 Repository Structure
```text
├── Data/                  # Source dataset files (CSV/Excel format)
├── Dashboard/             # Power BI Desktop template file (.pbix)
└── README.md              # Project documentation
