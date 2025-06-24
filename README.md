# Scenario-Based Modeling of 2025 Texas Measles Outbreaks

This repository contains the code and data supporting the study:  
**_“Assessing MMR Vaccination Strategies in Texas: A Scenario-Based Modeling Study of Measles Outbreaks”_**  
Bi et al., 2025 
DOI: [https://doi.org/10.1101/2025.03.25.25324613]

---

## 📄 Summary

This study evaluates the impact of the MMR vaccination strategies on measles transmission in Texas during the 2025 outbreak. Using a stochastic age-structured SEIR-HD model, we compare outbreak outcomes under different vaccine uptakes scenarios (baseline, 5% decrease, 5% increase).

---

## 📂 Repository Structure

├── gaines_case.csv
│ └── Reported measles cases in Gaines County
├── United_States_subnational_Texas_M_overall_contact_matrix_85.csv
│ └── Age-specific contact matrix for Texas
├── county_baseline_0621.csv
│ └── Simulation results for all counties (baseline scenario)
├── county_high_0621.csv
│ └── Simulation results for all counties with 5% vaccination reduction
├── county_low_0621.csv
│ └── Simulation results for all counties with 5% vaccination improvement
├── Measles_Model_v5.ipynb
│ └── Parameter estimation and simulation for Gaines County
├── map1_1.ipynb
│ └── Simulation code for baseline scenario across Texas
├── map2_1.ipynb
│ └── Simulation code for 5% vaccination reduction scenario
├── map3_1.ipynb
│ └── Simulation code for 5% vaccination improvement scenario
├── README.md
│ └── Project overview and usage guide (this file)
