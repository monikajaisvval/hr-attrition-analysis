# Business Insights & Recommendations
## HR Employee Attrition Analysis

---

### Dataset Overview
- Total employees analysed: **1,470**
- Overall attrition rate: **16.1%** (237 employees left)
- Note: Dataset is imbalanced (16% Yes vs 84% No) — addressed in model evaluation

---

### Insight 1 — Overtime is the strongest predictor of attrition
Employees who work overtime have an attrition rate of **30.5%**, compared to just **10.4%** for those who do not. This makes overtime the single most actionable lever for HR teams. The Sales and Human Resources departments have the highest proportion of overtime workers, which directly explains their elevated turnover.

**Recommendation:** Introduce overtime caps or compensatory policies in high-burnout departments. Monitor weekly hours as a leading indicator of flight risk.

---

### Insight 2 — Sales department needs immediate attention
The Sales department records the highest attrition rate at **20.6%**, followed by Human Resources at **19.0%**. Research & Development, despite being the largest department, has a comparatively lower rate of **13.8%**.

**Recommendation:** Conduct stay interviews in the Sales team to understand specific pain points. Review target-setting practices and commission structures that may be creating undue pressure.

---

### Insight 3 — Young employees (18–25) leave at disproportionate rates
The 18–25 age group shows the highest attrition across all age segments. This group typically occupies junior roles with lower salaries and limited career growth visibility, creating a higher propensity to explore other opportunities early.

**Recommendation:** Create structured career paths for junior employees. Pair new hires with senior mentors and set clear 6-month and 12-month growth milestones during onboarding.

---

### Insight 4 — Low salary is a key driver, especially in early tenure
Employees earning in the bottom income quartile have nearly **2x the attrition rate** of those in the top quartile. The risk is highest in the first 2 years of employment, before employees feel financially or culturally anchored to the organisation.

**Recommendation:** Benchmark entry-level salaries against industry standards annually. Consider a retention bonus at the 12-month and 24-month marks for roles with historically high turnover.

---

### Insight 5 — Employees with low job satisfaction and poor work-life balance are flight risks
Job satisfaction scores of 1 or 2 (out of 4) are strongly correlated with attrition. Similarly, employees rating their work-life balance as "Bad" leave at rates significantly higher than peers with "Good" or "Excellent" ratings.

**Recommendation:** Run quarterly pulse surveys to track satisfaction and work-life balance. Flag employees with consistently low scores for proactive HR conversations rather than waiting for resignation.

---

### Top 5 Features by Importance (Random Forest)
| Rank | Feature | Importance Score |
|------|---------|-----------------|
| 1 | OverTime | 0.148 |
| 2 | MonthlyIncome | 0.121 |
| 3 | Age | 0.108 |
| 4 | YearsAtCompany | 0.096 |
| 5 | JobLevel | 0.084 |

---

### Summary for Stakeholders
The data points to a clear pattern: **employees who are overworked, underpaid, early in their tenure, or disengaged are the most likely to leave**. Addressing overtime policies and entry-level compensation will deliver the highest immediate return on retention investment. Longer-term, improving job satisfaction monitoring and career pathing for young employees will reduce structural attrition.
