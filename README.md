# 🧑‍💼 Project PeopleFirst — Workforce Attrition & Retention Intelligence
 
## 📌 Project Overview
 
Every employee exit costs a company approximately **1.5x that employee's annual salary** in rehiring and retraining costs — yet most HR retention decisions are still made on gut feeling.
 
I built **Project PeopleFirst** to change that. Using the IBM HR Analytics dataset, this project moves beyond surface-level headcounts to deliver a data-driven narrative that answers two core business questions:
 
- **Who is leaving?** — Demographics, tenure, travel frequency, and manager relationships
- **Why are they leaving?** — Compensation gaps, overtime burden, growth stagnation, and satisfaction levels
The output is a **2-page interactive Power BI dashboard** designed to give HR leadership clear, targeted, evidence-based retention decisions.
 
---
 
### 📂 Files Included in this Repository
 
* **`PeopleFirst_Dashboard.pbix`**: The fully interactive 2-page Power BI dashboard.
* **`PeopleFirst_Dashboard.pdf`**: Static snapshot of both dashboard pages.
* **`Page1_WhoIsLeaving.png`**: Dashboard screenshot — Who Is Leaving?
* **`Page2_WhyAreTheyLeaving.png`**: Dashboard screenshot — Why Are They Leaving?
* **`People_first.csv`**: The raw dataset used for analysis.
* **`Demo_Video_Link.txt`**: YouTube demo walkthrough link.
---
 
## 🛠️ Tech Stack & Skills Demonstrated
 
* **Business Intelligence:** Microsoft Power BI — 2-page interactive dashboard
* **Data Preparation:** Power Query for data loading and profiling
* **Business Logic:** DAX Measures (Attrition Rate %, Active Employees, Avg Monthly Income, Avg Salary Hike %)
* **Data Engineering:** DAX Calculated Columns (Age Group, Salary Range, Tenure Groups, Satisfaction Labels, Stock Option Labels)
* **UI/UX Design:** Power BI (Custom purple theme, KPI cards, consistent color language across visuals)
---
 
## 🗃️ Dataset
 
* **Source:** IBM HR Analytics Employee Attrition Dataset (Kaggle)
* **Records:** 1,470 employees | 35 columns
* **Target Variable:** Attrition (Yes / No)
* **Key Features Used:** Age, MonthlyIncome, OverTime, JobSatisfaction, YearsAtCompany, YearsInCurrentRole, StockOptionLevel, YearsSinceLastPromotion, BusinessTravel, MaritalStatus
---
 
## 📊 Key Executive Insights
 
### 1. The Attrition Headline
 
Out of 1,470 employees, **237 have left** — an attrition rate of **16.12%**. With an average monthly income of **6.50K** and an average salary hike of just **15.21%**, the data immediately flags a compensation problem worth investigating.
 
### 2. Who Is Leaving — The Profile
 
The typical attriting employee is **aged 26-35, single, in their role for less than 2 years, and working under a relatively new manager**. This group accounts for nearly **49% of all exits** — making them the most expensive and most preventable segment to lose. These are early-career professionals leaving for better growth opportunities, not dissatisfied veterans burning out.
 
### 3. Why They Are Leaving — The Drivers
 
* **Salary is the #1 driver** — 163 out of 237 attrited employees (68.8%) earned below 5K monthly. This single band explains the majority of attrition.
* **Overtime is a risk multiplier** — Employees on overtime have a **30.5% attrition rate** vs **10.4%** for those who don't — nearly **3x higher**.
* **Stock options are underutilized** — Employees with no stock options show **24.4% attrition** vs **17.6%** for high-option holders. Financial ownership in the company is a meaningful retention lever being ignored.
* **Satisfaction alone doesn't retain people** — Even highly satisfied employees (level 4) show 52 exits, proving that compensation and growth matter more than satisfaction scores alone.
### 4. 🚨 The Counter-Intuitive Finding
 
Employees promoted within the last 0-1 years still show **159 exits**. This means the company is promoting people but still losing them — suggesting promotions are either too small, too late, or not accompanied by meaningful salary corrections. Promotion without compensation realignment is an ineffective retention strategy.
 
---
 
## 💡 Recommendations to HR Leadership
 
1. **Salary review for the below 5K band** — 68.8% of attrition originates here. A targeted 15-20% correction would have the most immediate retention impact.
2. **Structured growth path for 26-35 employees** — Introduce 18-month role progression milestones so early-career employees see a clear future before they look elsewhere.
3. **Regulate overtime policy** — Cap mandatory overtime or introduce compensatory benefits for regularly overworked employees.
4. **Expand stock option eligibility** — Extend even low-tier options to below 5K earners to create financial retention hooks for the most at-risk segment.
5. **New manager onboarding program** — Invest in structured manager training focused on early team retention and relationship building in the first 24 months.
---
 
## 🎨 UI/UX Design Approach
 
Designed with **HR Leadership readability** in mind:
 
* Custom deep purple theme (`#6B1F5E`) applied consistently across both pages for a premium portfolio look.
* KPI cards anchored at the top of each page so leadership reads the headline numbers before diving into charts.
* Consistent Yes/No attrition color language across every visual — no guesswork for the viewer.
* Grouped axis buckets (Age Group, Tenure Group, Salary Range) replacing raw numeric axes for cleaner, more business-friendly storytelling.
* Two-page structure separating *who* from *why* — reducing cognitive load and making the narrative easier to follow.
---
 
## 👤 Author
 
**Akshat Sharma** — Aspiring Data Analyst  
 
---
 
*This project is part of my data analytics portfolio. Dataset sourced from Kaggle — IBM HR Analytics Employee Attrition & Performance.*
