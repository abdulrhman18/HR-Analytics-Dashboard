# HR Analytics & Workforce Insight Dashboard

## 📊 Project Overview
This **Power BI Dashboard** provides a comprehensive analysis of a company's human resources data. It is designed to help HR managers and executives monitor workforce demographics, track employee promotion eligibility, and analyze retention risks (retrenchment) to support strategic decision-making.

## 🚀 Key Workforce Metrics (KPIs)
* **Total Employees:** 1,470
* **Gender Split:** 60% Male (882) | 40% Female (588)
* **Retention Status:** 92% On-Service | 8% Retrenchment (117 employees)
* **Promotion Pipeline:** 4.9% (72 employees) Due for promotion | 95.1% Not due

## 🔍 Key Insights
The dashboard features two main views: **Home** for general demographics and **Action** for targeted HR interventions.

### 1. Workforce Demographics & Tenure
* **Service Years:** The largest employee group has been with the company for **5 years (196 employees)**, followed closely by those with **1 year** of service.
* **Job Levels:** A significant majority of the workforce is concentrated in **Level 1 (543)** and **Level 2 (534)** positions.
* **Commute Analysis:** Nearly **70%** of employees live "very close" to the office, which is a positive indicator for long-term retention.

### 2. Employee Satisfaction & Performance
* **Satisfaction Ratings:** Over **84%** of the workforce reports "High" ratings, while **15.37%** are currently "Low Rated," signaling a need for performance reviews or engagement programs.
* **Overtime Impact:** A visual breakdown shows the distribution of employees working overtime vs. those who do not, helping identify potential burnout risks.

### 3. Departmental "Action" Analysis
* **Retrenchment vs. Promotion:** The **Research & Development** department has the highest number of employees due for promotion, but also significant retrenchment figures.
* **Role-Specific Data:** Managers and Sales Executives show the highest numbers in the "lay_off" (retrenchment) category, providing a clear starting point for organizational restructuring discussions.

## 🛠️ Tech Stack
* **Power BI Desktop:** Data visualization and report authoring.
* **DAX:** Implementation of complex measures for promotion logic and retrenchment percentages.
* **Power Query:** Data cleaning, particularly for grouping "Distance status" and "Service Years."

## 📂 How to Use
1.  Open the `.pbix` file in **Power BI Desktop**.
2.  Use the **Slicer Panel** on the left to filter data by *Business Travel, Education Field, Marital Status, OverTime,* and *Job Role*.
3.  Navigate between the **Home** and **Action** tabs using the buttons at the bottom or the navigation arrows in the header.
