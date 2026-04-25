# HR Analytics Dashboard

**Type:** Data Analytics Project | **Tool:** Power BI

An interactive Power BI dashboard built to analyze employee attrition, salary distribution, and workforce demographics, enabling data-driven HR decision-making.

Designed as a portfolio project to demonstrate data analysis, visualization, and business insight generation skills.

## Objective

To identify key drivers of employee attrition and provide actionable insights that help improve retention, optimize compensation, and understand workforce composition.

## Dashboard Preview

![HR Analytics Dashboard](https://github.com/user-attachments/assets/f60f260a-c0f7-49b0-b2b8-e63344cee449)

---

## Dataset

* `HR_Analytics.csv` — Employee-level dataset containing:

  * Demographics (Age, Gender, Education)
  * Job details (Department, Role, Salary Slab)
  * Tenure (Years at Company)
  * Attrition status

---

## Tools & Technologies

* **Power BI** — Data visualization & dashboard development
* **Power Query** — Data cleaning & transformation
* **DAX** — KPI calculations (Attrition Rate, Average Metrics, Role-wise Analysis)
* **CSV** — Data source

---

## Key Features

**Workforce Overview**

* Total Employees, Attrition Count & Rate
* Average Age, Salary, and Tenure

**Attrition Analysis**

* By Age Group (highest in 26–35)
* By Salary Slab (majority below 5K)
* By Education & Job Role
* By Years at Company (early attrition trend)

**Employee Demographics**

* Gender distribution
* Department-level filtering
* Job role vs satisfaction analysis

---

## Key Insights

* Overall attrition rate: **17%** across 1,312 employees
* Highest attrition in the **26–35 age group** (115 out of 223 employees)
* **161 out of 223 attritions (72%)** occur in the below-5K salary slab
* Significant drop-off within the **first year** of employment
* Roles most affected: **Laboratory Technician (61)** and **Sales Executive (52)**

---

## Business Impact

This dashboard enables HR teams to:

* Identify high-risk employee segments
* Take proactive retention measures
* Improve workforce planning and compensation strategies

---

## How to Use

1. Download the `.pbix` file from this repository
2. Open in **Power BI Desktop** (free download at [powerbi.microsoft.com](https://powerbi.microsoft.com))
3. The dashboard loads with all data pre-connected — no additional setup required
4. Explore filters (Department, Role, etc.) at the top to slice all visuals
5. Hover over any chart for detailed tooltips
6. To use your own data, go to **Home → Transform Data** and replace the source with your own `HR_Analytics.csv`

---

## Project Structure

```
HR_Analytics_Dashboard/
├── HR_Analytics_Dashboard.pbix     # Power BI dashboard file
├── HR_Analytics.csv                # Source dataset
└── HR_Analytics_Dashboard.pdf      # Static dashboard export (preview)
```

---

## Author

**Fizza Shabbir** — [LinkedIn](https://linkedin.com/in/fizzashabbir) | [GitHub](https://github.com/Fizza232)
