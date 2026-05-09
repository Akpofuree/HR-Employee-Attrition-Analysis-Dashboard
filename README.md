# HR Employee Attrition Analysis

## Project Overview

This project is an end-to-end data analysis of employee attrition patterns within a non-fictional organization. The goal is to move beyond simply knowing *that* employees are leaving and understand *who* is leaving, *why*, and *what patterns* exist — so that HR leadership can take targeted, data-driven action.

The project was built as a learning project covering the full data analyst workflow: data cleaning, SQL querying, dashboard building, and communicating findings.

---

## Tools Used

| Tool | Purpose |
|---|---|
| Microsoft Excel (Online) | Data cleaning, exploration, pivot tables |
| SQL (SQLiteOnline.com) | Querying and aggregating data |
| Power BI Desktop | Interactive dashboard for stakeholders |
| Google Looker Studio | Public-facing data story |

---

## Dataset

| Detail | Information |
|---|---|
| **Source** | Provided by a former employee who wishes to remain anonymous |
| **Size** | 1,470 rows × 35 columns |
| **Format** | CSV |
| **Original Reference** | IBM HR Analytics Employee Attrition & Performance Dataset |

The dataset contains employee demographic information, job role details, compensation data, satisfaction scores, and attrition status (whether the employee left or stayed).

---

## Business Problem

The organization is experiencing higher-than-expected employee turnover. At a 16.12% attrition rate — meaning roughly 1 in 6 employees has left — leadership needs to understand the root causes before investing in retention strategies.

This analysis was designed to answer 7 specific business questions that target the most common drivers of attrition in HR research.

---

## Business Questions Answered

1. Which department has the highest attrition rate?
2. Do employees who work overtime leave more often?
3. Does monthly income affect employee attrition?
4. Which age group experiences the highest attrition?
5. Which job role is most at risk of high attrition?
6. Does job satisfaction affect employee attrition?
7. Does work-life balance influence attrition?

---

## Key Findings

### Overall Attrition
- **Total Employees:** 1,470
- **Employees Who Left:** 237
- **Overall Attrition Rate:** 16.12%

---

### Q1 — Department with Highest Attrition
**Finding:** The Sales department recorded the highest attrition rate at **20.63%**, followed by Human Resources at **19.05%**. Research & Development had the lowest rate at **13.84%** despite having the most employees overall.

**Lesson:** Raw headcount and attrition rate are different things. A large department can have fewer leavers proportionally than a smaller one.

---

### Q2 — Overtime and Attrition
**Finding:** Employees working overtime had an attrition rate of **30.53%** compared to just **10.44%** for those who did not work overtime — nearly 3 times higher.

**Lesson:** Overtime is one of the strongest attrition signals in this dataset. Extended hours strongly predict employee departure.

---

### Q3 — Monthly Income and Attrition
**Finding:** Employees who stayed earned an average monthly income of **6,832.74**, while employees who left earned significantly less at an average of **4,787.09**.

**Lesson:** Compensation is a major pull factor in attrition. Employees leaving for better pay is a pattern the data clearly supports.

---

### Q4 — Age Group and Attrition
**Finding:** The **18–25 age group** had the highest attrition rate at **35.77%**, followed by the **26–35 group** at **19.14%**. Attrition decreased steadily with age after that.

**Lesson:** Early-career employees are the most mobile and hardest to retain. Career development and mentorship programs targeting younger staff could have high impact.

---

### Q5 — Job Role Most at Risk
**Finding:** **Sales Representatives** had the highest attrition rate at **39.76%**, followed by Laboratory Technicians at **23.94%** and Human Resources roles at **23.08%**. Research Directors and Managers had the lowest rates.

**Lesson:** High-pressure, target-driven roles face the greatest retention challenges. Seniority and stability appear to reduce attrition risk.

---

### Q6 — Job Satisfaction and Attrition
**Finding:** Employees with the lowest job satisfaction score (Level 1) had the highest attrition rate at **22.84%**. Higher satisfaction scores corresponded with lower attrition rates.

**Lesson:** Job satisfaction is directly tied to retention. Culture, management quality, and role fulfilment matter significantly.

---

### Q7 — Work-Life Balance and Attrition
**Finding:** Employees with the poorest work-life balance had the highest attrition. Interestingly, employees with the best work-life balance score also showed elevated attrition — suggesting other factors like compensation or growth may be influencing their decision to leave.

**Lesson:** Work-life balance matters, but it does not operate in isolation. Employees with good balance can still leave if other needs are unmet.

---

## HR Recommendations

Based on the findings above, the following actions are recommended for HR leadership:

**1. Address Overtime Culture**
Overtime is the strongest attrition signal in this dataset. Reviewing workload distribution, hiring additional staff in high-overtime roles, and setting clearer boundaries around working hours could significantly reduce burnout-driven attrition.

**2. Review Compensation for Lower-Earning Roles**
Employees who left earned on average 30% less than those who stayed. A targeted compensation review — especially for Sales Representatives and Laboratory Technicians — is strongly advised.

**3. Build Retention Programs for Young Employees**
The 18–35 age bracket accounts for the majority of attrition. Structured mentorship programs, clear career progression frameworks, and improved onboarding experiences could meaningfully reduce early-career departures.

**4. Prioritise the Sales Department**
Sales recorded both the highest departmental attrition rate and the highest job-role attrition rate. A dedicated investigation into the Sales team environment, targets, and compensation structure is recommended.

**5. Invest in Employee Satisfaction Initiatives**
Low job satisfaction clearly predicts attrition. Regular pulse surveys, manager training, and role enrichment opportunities can help surface and address dissatisfaction before it becomes resignation.

**6. Investigate High Work-Life Balance Attrition**
The unexpected attrition among employees reporting the best work-life balance warrants further investigation. Exit interview data and additional variables (such as career growth or manager relationships) should be explored.

---

## Project Structure

```
HR-Attrition-Project/
│
├── 1 - Raw Data/
│   └── WA_Fn-UseC_-HR-Employee-Attrition.csv
│
├── 2 - Excel Work/
│   └── HR_Attrition_Cleaned.xlsx
│
├── 3 - SQL Queries/
│   └── hr_attrition_analysis.sql
│
├── 4 - Power BI/
│   └── HR_Attrition_Dashboard.pbix
│
├── 5 - Summary/
│   └── README.md
```

---
---
 Here is a link to see the powerbi presentation
 https://www.loom.com/share/5c209ec4e4c54cef83a1ae6f3fc322dd


## Author

**Akpofure**
HR Professional | Data Analyst in Training
Lagos, Nigeria

Skills demonstrated in this project: Data Cleaning, SQL Querying, DAX Measures, Power BI Dashboard Design, Data Storytelling, HR Analytics

---

