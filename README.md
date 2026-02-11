# 📊 User Acquisition Analysis  
### Customer Acquisition Audit & Exploratory Data Analysis (EDA)

---

## 🛠️ Tech Stack

[![My Skills](https://skillicons.dev/icons?i=python,r,mysql)](https://skillicons.dev)

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)
![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

---

## 📌 Project Overview

This project was completed during my internship at a UK-based company.  
The objective was to conduct a **Data Quality Audit** and perform **Exploratory Data Analysis (EDA)** on customer sign-up data to generate actionable insights for the **Marketing** and **Onboarding** teams.

The dataset contains:

- **291 rows**
- **10 columns**
- Features include:
- python ['customer_id', 'name', 'email', 'signup_date', 'source', 'region', 'plan_selected', 'marketing_opt_in', 'age', 'gender']



## 🎯 Project Objectives

- Identify inaccurate or incomplete data  
- Analyze user acquisition sources  
- Evaluate plan selection trends  
- Assess marketing opt-in behavior  
- Explore demographic patterns  

---

## 🧹 Data Quality Audit

**Issues Identified & Resolved**

- Removed duplicate entries  
- Corrected `age = 0` outliers  
- Reviewed missing / inconsistent regional data  
- Validated `signup_date` formatting  

> Result: Ensured high data reliability for downstream analysis and reporting.

---

## 📊 Key Business Insights

### 1. Top Acquisition Channel

- **Google** generated the highest number of users  
- **YouTube** ranked as the second strongest acquisition source  

**Business Impact**  
Focus budget allocation on high-performing Google Ads campaigns to maximize ROI.

---

### 2. Regional Performance & Data Gaps

- Minor missing or incomplete regional entries detected  
- **Central region** recorded the lowest signup volume  

**Business Impact**  
Opportunity to strengthen campaign penetration in underperforming regions.

---

### 3. Age vs Marketing Opt-In Behavior

**Statistical Summary**

| Metric | Opt-In | Non-Opt-In |
|--------|--------|------------|
| Median Age | 34 | 34 |
| IQR | 25–40 | 25–40 |

Boxplot comparison shows no statistically significant difference between groups.

**Business Insight**  
Age is not a primary driver of marketing engagement.  
Segmentation strategies should instead focus on **acquisition source** or **plan type**.

---

### 4. Plan Selection by Age & Region

- Users aged ~29 primarily choose the **Basic Plan**  
- Users aged ~35 show higher adoption of **Premium** and **Pro Plans**  
- **North region** leads Premium adoption (34 users)  

**Business Insight**  
Upselling strategies may perform best within the 30–40 age segment.  
Plan positioning can be optimized based on age clustering.

---

### 5. Source vs Plan Conversion Patterns (Heatmap Analysis)

- YouTube → Higher concentration in **Basic Plan**  
- Google → Stronger conversion to **Pro Plan**  
- Facebook → Balanced mid-tier engagement  

**Business Impact**  
Different acquisition channels attract distinct pricing sensitivities.  
Campaign messaging should be customized per source.

---

## 📈 Visual Analysis Performed

- Channel distribution (Countplot)  
- Source vs Plan heatmap  
- Age vs Plan boxplots  
- Age distribution histograms  
- Regional signup distribution analysis  

---

## 📌 Strategic Recommendations

- Increase investment in high-performing acquisition channels (Google)  
- Improve onboarding UX for Basic plan users  
- Target 30–40 age segment for premium upselling  
- Reassess campaign effectiveness in the Central region  
- Implement source-based segmentation in marketing strategy  

---

## 🚀 Business Value Delivered

- Enhanced data integrity and reliability  
- Identified high-ROI acquisition channels  
- Uncovered pricing sensitivity trends  
- Delivered actionable insights to Marketing & Onboarding teams  
- Enabled data-driven decision making  

---

## 📎 Project Classification

`Internship Project` · `Data Quality Audit` · `EDA` · `Marketing Analytics`

---
