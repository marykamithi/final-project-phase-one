# final-project-phase-one
This is the link to my tableau public visualizaions https://public.tableau.com/app/profile/mary.kamithi/viz/Aviationdata_17509279068140/Dashboard1
I did three visualizations whereby i analyzed :
  the number of fatal deaths per year
  phase of flight vs the fatalities
  aircraft damage vs the sum of fatalities
  Here's a full `README.md` template tailored to your **Aviation Accident Risk Analysis** project, following all the requirements you listed:


# Aviation Accident Risk Analysis

## Overview

This project analyzes aviation accident data to help stakeholders within a company identify the safest types of aircraft for potential investment. The analysis explores patterns in accident severity, aircraft damage, and flight phases, providing data-driven recommendations for minimizing fatal risk.



##  Business Understanding

The company is expanding into the aviation industry and needs to understand the risks associated with different types of aircraft and conditions to make informed purchasing decisions.

###  Stakeholder

The primary stakeholder is the Head of the Aviation Division, who will use this analysis to guide investment decisions.

###  Key Business Questions

- What types of accidents are most likely to be fatal?
- Which aircraft damage types or flight phases are associated with fatalities?
- How have fatal accidents changed over time?


##  Data Understanding and Analysis

###  Source of Data

- **Dataset:** National Transportation Safety Board (NTSB) Aviation Accident Database  
- **Files Used:**
  - `AviationData.csv`
  - `USState_Codes.csv`

### Description of Data

The dataset includes:
- Event details (date, location, phase of flight)
- Aircraft information (type, damage, engines)
- Injury counts (fatal, serious, minor)
- Environmental conditions (weather)
- ~88,000 accident records spanning from 1962 to 2023


###  Visualizations

#### 1.  Fatal Accidents Over Time
> **Chart:** Line chart of number of fatal accidents per year  
 Fatal accidents have generally decreased over the decades, especially after 2000.

#### 2.  Aircraft Damage vs. Fatal Accidents
> **Chart:** Bar chart comparing aircraft damage types with fatality counts  
> **Insight:** Substantial and destroyed aircraft damage are most commonly linked to fatal outcomes.

#### 3.  Phase of Flight vs. Fatal Risk
> **Chart:** Bar chart of flight phases vs. fatal accident ratio  
> **Insight:** Takeoff and landing phases have the highest proportion of fatal accidents.

>

##  Conclusion

### 📌 Summary of Key Findings

- **Aircraft Damage:** Fatalities are strongly associated with substantial or destroyed damage.
- **Flight Phases:** Takeoff, en-route, and landing are the most critical phases for fatal risks.
- **Trend Over Time:** Overall, aviation accidents—especially fatal ones—have declined over the last two decades.

These insights support  decisions in aircraft selection and flight safety planning.


## 📜 Commit History

- Maintained a clean and consistent commit history throughout the project.
- Each commit includes clear messages such as:
  - `Initial EDA and null handling`
  - `Created is_fatal column`
  - `Added visualizations for phase of flight`
  - `Finalized Tableau dashboards`



##  Organization

aviation-risk-project/
├── README.md
├── .gitignore
├── presentation.pdf
├── student.ipynb
├── notebook.pdf
├── cleaned\_data.csv
├── Tableau\_Screenshots/
│   ├── fatal\_over\_time.png
│   ├── damage\_vs\_fatal.png
│   └── phase\_vs\_fatal.png
└── dashboard\_link.txt



##  Notebook(s)

- **Final Notebook:** `student.ipynb` — includes cleaned dataset, EDA, feature engineering, and visualizations
- **Cleaned Notebook** `cleaned.csv` - the cleande data



## 🚫 .gitignore

Custom `.gitignore` file includes:
```

.DS\_Store
.ipynb\_checkpoints/
\*.csv
\*.png
\*.zip
.env
**pycache**/

```

> Based on GitHub’s [Python .gitignore](https://github.com/github/gitignore/blob/main/Python.gitignore) with project-specific additions.

---

## 📎 Extras

-  Tableau Dashboard :  
  [https://public.tableau.com/app/profile/mary.kamithi/viz/Aviationdata_17509279068140/Dashboard1]







  
