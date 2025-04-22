# Natural Drivers of Coastal Erosion
---

## Overview

This project aims to investigate the **natural drivers of coastal erosion** using a combination of simulated environmental data, exploratory data analysis (EDA), and machine learning techniques. The goal is to identify key contributing factors and develop a predictive model to estimate coastal erosion rates. The study highlights the importance of a multivariate and non-linear approach for understanding these complex environmental interactions.

---

## Objectives

- Identify and understand the primary natural drivers of coastal erosion.
- Analyze relationships and dependencies among these variables.
- Develop a machine learning model to predict coastal erosion rates.
- Provide insights applicable to coastal zone management and erosion mitigation strategies.

---

## Key Topics

### Natural Drivers Considered
- **Wave Dynamics**  
- **Tidal Patterns**  
- **Storm Frequency**  
- **Sea-Level Rise**  
- **Sediment Transport**  
- **Geological Factors**

Each of these components plays a role in the coastal erosion process, either directly or through interactions with other factors.

---

## Methodology

### Data Simulation
- Synthetic dataset generated using realistic statistical distributions:
  - Wave Energy (Gamma)
  - Tidal Range (Lognormal)
  - Sediment Transport Rate (Linear)
  - Sea-Level Rise (Beta)
  - Storm Frequency (Poisson)
  - Erosion Rate (Composite non-linear function)

### Exploratory Data Analysis
- Correlation analysis
- Distribution visualization
- Bivariate scatter plots and kernel density estimation

### Model Development
- **Random Forest Regressor** (100 trees, max depth = 10)
- 80/20 training/test split
- Evaluated using R² score and Mean Squared Error

---

## Results

### Model Performance
- **R² Score:** 0.4088  
- **Mean Squared Error:** 0.1401

### Feature Importances
- Wave Energy: 49.26%  
- Tidal Range: 19.81%  
- Sediment Transport: 13.97%  
- Sea-Level Rise: 11.83%  
- Storm Frequency: 5.13%

The results indicate that wave energy is the most significant predictor, followed by tidal and sediment transport processes.

---

## Limitations

- Simulated data may not capture the full complexity of real-world coastal systems.
- Seasonal and temporal variations are not included.
- Human interventions (e.g., seawalls, groynes) are excluded.
- Regional geological variations are generalized.

---

## Future Work

- Incorporate real-world coastal datasets and time-series information.
- Include anthropogenic factors and engineering structures.
- Utilize high-resolution remote sensing data.
- Explore advanced modeling approaches, such as deep learning.

---

## References

[1] https://openrepository.aut.ac.nz/items/c668a03e-c5a5-4022-bbb1-49e4222eb122

[2] “Coastal Sediment Transport.” Available:  
https://www.wa.gov.au/system/files/2023-09/fs4-coastal-sediment-transport.pdf

[3] R. Vallarino, V. N. Valdecantos, and D. Campo, “Understanding the impact of hydrodynamics on coastal erosion in Latin America: a systematic review,” *Frontiers in Environmental Science*, vol. 11, Oct. 2023.  
https://doi.org/10.3389/fenvs.2023.1267402

[4] L. Mentaschi, M. I. Vousdoukas, J.-F. Pekel, E. Voukouvalas, and L. Feyen, “Global long-term observations of coastal erosion and accretion,” *Scientific Reports*, vol. 8, no. 1, Aug. 2018.  
https://doi.org/10.1038/s41598-018-30904-w

[5] M. Jamous, R. Marsooli, and J. K. Miller, “Physics-based modeling of climate change impact on hurricane-induced coastal erosion hazards,” *npj Climate and Atmospheric Science*, vol. 6, no. 1, pp. 1–10, Jul. 2023.  
https://doi.org/10.1038/s41612-023-00416-0

[6] “This resource has been produced by Newground who work in partnership with the Environment Agency.”  
https://thefloodhub.co.uk/wp-content/uploads/2020/02/FT-Q-R117-A-Changing-Coastline-The-impacts-and-how-we-can-adapt.pdf

[7] Causeartist, “Coastal Erosion: Causes, Effects, and Solutions,” *Causeartist*, Mar. 06, 2025.  
https://www.causeartist.com/coastal-erosion-causes-effects-and-solutions/

[8] National Park Service, “Coastal Processes—Sediment Transport and Deposition (U.S. National Park Service),” *Nps.gov*, 2019.  
https://www.nps.gov/articles/coastal-processes-sediment-transport-and-deposition.htm

---

