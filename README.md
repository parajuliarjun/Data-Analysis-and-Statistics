### Data Analysis & Statistics: Hydrological & Spatial Data Analytics

This repository contains data analysis workflows, statistical modeling, and geospatial processing pipelines developed during my Master's studies in Hydro Science and Engineering at TU Dresden (Institute of Hydrology and Meteorology).

---

### Key Projects & Focus Areas

#### 1. Comparative Analysis of Air Temperature Trends (2005–2025)
* **Objective:** Quantify long-term regional warming rates and investigate urban vs. suburban thermal dynamics by comparing Dresden-Klotzsche and Berlin-Tempelhof.
* **Methodology:** Applied non-parametric Mann-Kendall trend tests and Sen's Slope Estimators via the tidyverse framework in R to handle outliers and non-normal distributions.
* **Key Findings:** Revealed a statistically significant warming trend of +0.818 °C per decade (p = 0.0048) in Berlin, reflecting accelerated urban heat island (UHI) amplification compared to suburban Dresden (+0.420 °C/dec).

#### 2. Statistical Analysis of River Discharge: Elbe River
* **Objective:** Characterize long-term flow regimes, evaluate extreme flood events, and contrast wet versus dry hydrological years using historical discharge records (since 1806).
* **Methodology:** Evaluated discharge distribution transformations (log-normal, shifted log-transform), performed Extreme Value Analysis (EVA) to estimate the 100-year flood (Q100), and analyzed seasonal cumulative sums and density distributions.
* **Key Findings:** The log-normal EVA model estimated a theoretical 100-year flood of 4,634 m^3 s^-1 (compared to an empirical 4,409 m^3 s^-1), providing a robust safety margin for flood risk management. Contrast analyses between extreme years (e.g., 1941/2002 wet years vs. 1864/1943 dry years) highlighted distinct seasonal hydrograph behaviors.

---

### Repository Contents & Reports
* 📄 [Comparative Analysis of Air Temperature Trends.pdf](Comparative%20Analysis%20of%20Air%20Temperature%20Trends.pdf): Full DWD climate data analysis report with Sen's slope calculations and trend visualizations.
* 📄 [Statistical Analysis of River Discharge.pdf](Statistical%20Analysis%20of%20River%20Discharge.pdf): Comprehensive Elbe River discharge report covering distribution transformations, EVA, and seasonal regime comparisons.
* `scripts/`: Modular R scripts for data processing, statistical testing, and automated plotting (ggplot2).
