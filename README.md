## 📊 Main Analysis Notebook
The primary capstone analysis (code, narrative, and visualizations) is available here:
👉 [Open the analysis notebook](notebooks/cape_fur_seal_entanglements_2021_2025.ipynb)
# Spatial, Temporal, and Demographic Patterns of Cape Fur Seal Entanglements (2021–2025)
## Project Overview
Marine debris entanglement is a growing threat to Cape fur seals along Namibia’s coast, particularly near major breeding colonies such as Pelican Point and Cape Cross. This project analyzes entanglement incidents recorded between 2021 and 2025 using environmental data science methods.
## Research Question
How do different marine debris types vary spatially, temporally, and demographically in Cape fur seal entanglement incidents along the Namibian coast?
## Data
The dataset documents individual entanglement events recorded during monitoring and rescue operations.
Each record includes:
- Date and time of observation
- Colony and location
- Debris category and item type
- Seal age and sex
- Severity of entanglement
- Management action and outcome
Each observation represents a single entanglement event.
## Methods
The analysis uses several techniques from the Environmental Data Science program:
- Data cleaning and preprocessing using R and tidyverse
- Exploratory Data Analysis (EDA)
- Descriptive statistics
- Visualization of debris composition and demographic patterns
- Temporal trend analysis
- Spatial interpretation of entanglement hotspots
## Key Findings 
This project analyzes Cape fur seal entanglement incidents along the Namibian coast from 2021–2025. Using exploratory data analysis and visualization, the study identifies spatial hotspots, seasonal patterns, and debris types responsible for entanglements. Results show industrial and fishing debris dominate incidents, supporting geographically targeted and time-sensitive conservation interventions.
## Conservation Implications
Entanglement events cluster near Pelican Point and Cape Cross and show seasonal peaks. Because these incidents are spatially concentrated and temporally patterned, conservation actions such as debris removal, fisheries gear management, and targeted monitoring can reduce preventable wildlife harm.

## Repository Structure

cape-fur-seal-entanglement-analysis/
│
├── README.md              ← Project overview and summary
│
├── data/
│   └── Cape Fur Seal Entanglements 2021_2025.csv   ← Dataset
│
├── notebooks/
│   └── C5M15_practice-set (2).ipynb                ← Analysis notebook
│
├── figures/
│   ├── Composition of entanglement events.png     ← Debris composition
│   ├── Boxplot of entanglement severity.png       ← Severity analysis
│   └── Monthly trends in events.png               ← Time trends

## Key Visualizations
### Composition of Entanglement Events
![Composition](Composition%20of%20entanglement%20events.png)
### Entanglement Severity by Debris Category
![Severity](Boxplot%20of%20entanglement%20severity.png)
### Monthly Trend of Entanglement Events
![Trend](Monthly%20trends%20in%20events.png)
## Tools
R, tidyverse, ggplot2  



Milton Kimbini | Yale School of the Environment | Environmental Data Science Certificate (2025–2026)
