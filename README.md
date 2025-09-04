# 🍺 Alcohol-Related Diseases and Deaths in the United Kingdom (2001–2020)

A data analysis of alcohol-related disease burden and mortality across the four UK nations—**England, Scotland, Wales, Northern Ireland**—from **2001 to 2020**. The project surfaces long-term trends, regional disparities, and public health implications.

---

## Table of Contents
- [Objectives](#objectives)
- [Data Sources](#data-sources)
- [Data Description](#data-description)
- [Methodology](#methodology)
- [Results (Highlights)](#results-highlights)
- [Public Health Implications](#public-health-implications)
- [License](#license)
- [Author](#author)

---

## Objectives
- Track **annual trends** in alcohol-related diseases and deaths (2001–2020).
- Compare **regional differences** across the four UK nations.
- Estimate **rates per 100,000** to account for population changes.
- Provide **actionable insights** for policy and prevention.

---

## Data Sources
- **Office for National Statistics (ONS)**
- **NHS Digital / Public Health Scotland / Public Health Wales / Department of Health (NI)**
- **ONS Mid-year Population Estimates** (for rate denominators)

> Replace with exact datasets/links used in your repo’s `data/README.md`.

---

## Data Description
Minimum expected fields:

| Field | Description |
|------|-------------|
| `Year` | Calendar year, 2001–2020 |
| `Region` | England, Scotland, Wales, Northern Ireland |
| `Deaths_Alcohol_Related` | Number of deaths registered as alcohol-related |
| `Disease_Cases_Alcohol_Related` | Recorded incidence/admissions (if available) |
| `Population` | Mid-year population estimate |
| `Rate_Deaths_per_100k` | Derived: (Deaths / Population) × 100,000 |
| `Rate_Disease_per_100k` | Derived: (Cases / Population) × 100,000 |
| `Sex`, `Age_Group` | Optional stratifiers if available |

---

## Methodology
1. **Ingestion & Cleaning**
   - Import CSVs, harmonize column names and region labels.
   - Handled missing values; ensured Year is numeric and complete.

2. **Standardization**
   - Compute **rates per 100,000** using population estimates.

3. **Exploratory Data Analysis**
   - Trend lines by region and UK total.
   - Compared mean/median rates by period.


---

## Results (Highlights)
- Scotland showed the **highest rates** in early 2000s with **later declines**.
- England had **lower rates** but **highest absolute counts** due to population size.
- Post-2010 trends diverged across regions; policy timing appears relevant.

---

## Public Health Implications

Sustained monitoring of alcohol harm is essential for targeted interventions.

Regions with persistently high rates may benefit from pricing, availability, and treatment policies.

Pair analytics with community-level prevention and treatment access.



## License

Released under the MIT License. See LICENSE.

## Author

Peter S. Naroka — Public Health Data Analysis
For questions: narokapeter@gmail.com
