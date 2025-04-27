# Data Analysis Portfolio (2020)

![Tableau](https://img.shields.io/badge/Tableau-2020.1-orange)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13-blue)
![Excel](https://img.shields.io/badge/Excel-365-green)

Collection of data analysis projects from 2020 demonstrating business insights generation through visualization and statistical analysis.

## Projects

### 🚴 Bikehaven Fitness Analytics
**Tools**: Tableau, Excel  
**Scope**: 
- Analyzed 50K+ user activity records
- Identified sleep pattern correlations with workout performance
- Developed 6 interactive dashboards tracking:
  - Daily activity trends
  - Heart rate variability
  - Calories burned by exercise type

**Sample Insight**:  
*Users who slept 7-8 hours showed 23% better workout consistency*

[![View Dashboard](https://img.shields.io/badge/Tableau-Public-ff69b4)](https://public.tableau.com/)

---

### ⌚ Fitbit Data Analysis (WeFit)
**Tools**: Excel (Power Query, PivotTables)  
**Key Deliverables**:
- Processed 12 months of tracker data (steps, sleep, active minutes)
- Created segmentation models for marketing campaigns
- Automated monthly KPI reports (30% time savings)

**Visualization**:  
<img src="https://via.placeholder.com/600x300?text=WeFit+Performance+Dashboard" width="80%">

---

### 🏏 IPL Cricket Analysis 
**Tech Stack**: PostgreSQL, Excel  
**Analysis**:
```sql
-- Top batsmen by strike rate
SELECT player, ROUND(runs/balls*100,2) AS strike_rate 
FROM batting_stats 
WHERE balls > 100 
ORDER BY strike_rate DESC 
LIMIT 5;
