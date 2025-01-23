# Healthcare-Analytics
Healthcare and Hospital Data Analysis: Insights into discharges, patient days, and revenue trends (2016–2020) using Excel, MySQL, and Power BI. Includes challenges, solutions, and recommendations for improvement.


## Overview
This project analyzes healthcare and hospital data from 2016 to 2020, focusing on key metrics such as total discharges, patient days, and revenue trends. It highlights insights at the hospital type, county, and state levels and provides actionable recommendations for improvement.

---

## Table of Contents
- [Overview](#overview)
- [Key Metrics and Insights](#key-metrics-and-insights)
- [Challenges and Solutions](#challenges-and-solutions)
- [Tools and Technologies](#tools-and-technologies)
- [License](#license)

---

## Key Metrics and Insights

### Total Discharges Trend
- **2016:** 0.9M  
- **2019 (Peak):** 3.8M  
- **2020:** 2.2M (likely impacted by COVID-19)  
- **Overall Total:** 13.65M  

#### By Hospital Type:
- **Comparable Hospitals:** 11.07M discharges  
- **Kaiser Foundation Health:** 2.484M  
- Specialized facilities (e.g., Psychiatric): Smaller contributions  

#### By County:
- **Los Angeles:** 3.896M  
- **San Diego:** 1.096M  
- Other counties had significant disparities, many below 100K.

---

### Total Patient Days
- **Total:** 82.10M across all facilities.  
- **Peak Year:** 2019.  

#### By County:
- **Los Angeles:** 22.6M  
- **San Diego:** 6.1M  
- **San Bernardino:** 5M  

#### By Hospital Type:
- Comparable Hospitals and Kaiser Foundation Health contributed the majority of patient days.

---

### Total Revenue
- **Overall:** $474.55B  
- Steady growth from 2016 to 2020.  

#### By County:
- **Los Angeles:** $121B  
- **San Diego:** $37B  
- **Santa Clara:** $29B  

#### By Hospital Type:
- **Comparable Hospitals:** $404.55B (highest)  
- **Kaiser Foundation Health:** $62.91B  

#### Quarterly & Yearly Insights:
- QTD and YTD revenue showed consistent positive growth.  
- Significant revenue spike in Q2 2020 due to COVID-19.

---

## Recommendations
1. Expand telemedicine to maintain patient volumes during crises.  
2. Address regional disparities by improving healthcare access in underserved counties.  
3. Optimize smaller hospital contributions and leverage specialized care.

---

### Challenges and Solutions

#### Challenges:
1. **Understanding Data:** Short forms in headers were unclear.  
2. **Large Data Size:** 113 columns caused lag during analysis.  
3. **File Corruption:** Some CSV files were corrupted.  
4. **Dashboard Clutter:** Displaying all states cluttered the dashboard.

#### Solutions:
- Simplified headers using ChatGPT for clarification.  
- Reduced unnecessary columns for performance.  
- Recovered corrupted files.  
- Added a Top-n parameter for state-level analysis.

---

## Tools and Technologies
- **Data Cleaning and Modeling:** Microsoft Excel, MySQL  
- **Visualization:** Power BI, Tableau
- **Additional Support:** ChatGPT  

---

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.



   
