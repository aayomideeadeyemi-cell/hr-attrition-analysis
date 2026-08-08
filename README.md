# hr-attrition-analysis
HR employee attrition analysis using Excel — identifying which factors are most associated with turnover, based on 561 cleaned employee records.

## Business Problem
HR leadership noticed turnover creeping up but didn't know which employees were most at risk of leaving or why. This analysis works through cleaned employee records to identify the real drivers of attrition.

## Tools Used
Excel (data cleaning, COUNTIFS-based segmentation analysis)

## Method
Cleaned a raw HR dataset — standardized inconsistent department names, removed duplicate records, handled missing values, and corrected invalid hire dates. Calculated attrition rate (Left ÷ (Left + Stayed)) segmented by Department, Overtime status, Job Satisfaction, and Tenure.

## Key Findings
- **Overtime is the single biggest driver of attrition** — employees working overtime leave at more than double the rate (44.1%) of those who don't (19.9%)
- **Low job satisfaction nearly doubles attrition risk** — employees rating satisfaction at 1/4 leave at 41.8%, compared to 18.5% for those rating it 3/4
- **Sales has a noticeably higher attrition rate (33.8%)** than Human Resources (23.9%) or Research & Development (24.1%)
- **New employees (0-2 years tenure) leave at a substantially higher rate (31.0%)** than employees with 10+ years at the company (20.8%)
- Overall company attrition rate: **27.6%**

## Recommendations
- Audit overtime distribution, starting with Sales, and address workload imbalances driving burnout
- Investigate root causes of low job satisfaction scores (management, workload, growth opportunities) through targeted surveys or exit interviews
- Build a structured onboarding and check-in process for employees in their first 2 years, since this is the highest-risk tenure window
## Files
- `hr_attrition_analysis.xlsx` — raw data, cleaned data, cleaning log, attrition summary, and findings/recommendations
