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
gaines_case.csv/ # Reported measles cases in Gaines county
United_States_subnational_Texas_M_overall_contact_matrix_85.csv/ # Contact matrix
county_baseline_0621.csv/ # Simulation results for all counties under baseline scenario
county_high_0621.csv/ # Simulation results for all counties under scenario of 5% vaccination reduce 
county_low_0621.csv/ # Simulation results for all counties under scenario of 5% vaccination improve
Measles_Model_v5.ipynb/ # Code for parameter estimation and simulation for gaines county
map1_1.ipynb/ # Code for simulation for all counties under baseline scenario
map2_1.ipynb/ # Code for simulation for all counties under scenario of 5% vaccination reduce 
map3_1.ipynb/ # Code for simulation for all counties under scenario of 5% vaccination improve
README.md # This file
