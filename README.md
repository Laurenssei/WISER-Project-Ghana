# WISER-Project-Ghana

# WISER Project Ghana: How Does Social Capital Contribute to Well-Being in Times of Economic Challenges? Target Group: Street Vendors and Hawkers (Only Women): Exploratory Data Analysis

📄 Full Report: [View Analysis](SET 1 & 2 WISER PROJECT GHANA_ HOW DOES SOCIAL CAPITAL CONTRIBUTE TO WELL-BEING IN TIMES OF ECONOMIC CHALLENGE .pdf)

## Overview
The WISER Project in Ghana investigates the role of social capital in enhancing the well-being of 704 female street vendors and hawkers facing economic challenges, using survey data collected in April 2025. Exploratory data analysis reveals that vendors, predominantly aged 25–44 with a mean daily income of 187 GHS, encounter significant economic stressors, including sudden price increases (55.0%) and high competition (29.1%). Social capital, with a mean score of 2.68/5, significantly mitigates these challenges, driven by strong family support (mean: 3.24/5) and large social networks (47.3% with 8+ daily contacts), contributing to relatively high well-being (mean: 3.72/5, 83.4% high/very high). However, gaps in preferred versus received support are notable, particularly for protection (77.4%) and childcare (50.3%). Geographic disparities highlight Asokwa as the most vulnerable area (mean vulnerability: 3.46/5, well-being: 2.84/5), contrasting with Oforikrom’s lower vulnerability (1.73/5). Health issues, led by malaria (43.9%), and moderate commutes (15–60 minutes, linked to 205 GHS income) further shape vendor experiences. Cluster analysis identifies four vendor groups, with 12.8% in the most vulnerable cluster requiring urgent intervention. Policy recommendations include expanding microfinance, business training, and social protection measures, particularly in high-vulnerability areas like Asokwa, to leverage social capital and address unmet needs.

## Objectives
- Examine demographic and economic profiles of female street vendors and hawkers.
- Analyze business challenges, vulnerabilities, and their impacts on well-being.
- Assess the role of social capital and support systems in mitigating economic stressors.
- Evaluate health, safety, and accessibility factors influencing daily experiences.
- Identify geographic disparities and develop evidence-based policy recommendations.

## Dataset Summary
- **Source**: Primary survey data from female street vendors and hawkers in Kumasi, Ghana (April 2025).
- **Sample Size**: 704 respondents.
- **Key Variables**: Demographics (age, gender, marital status, education, residence); economic (income, work hours, challenges); social capital (family support, networks, trust); well-being (scores, satisfaction); health (issues, insurance); vulnerability (income instability, exclusion); support (received/preferred).

## Methods
- Descriptive statistics (means, frequencies, percentages) and visualizations (bar plots, histograms, box plots) for profiling demographics, challenges, and distributions.
- Correlation analysis (Pearson's r) for relationships (e.g., social capital vs. well-being, r=0.641).
- Principal component analysis (PCA) for dimensionality reduction (5 PCs explaining 93.87% variance).
- K-means clustering for vendor groups (4 clusters based on vulnerability, well-being, social capital).
- ANOVA/chi-square for group differences (e.g., vulnerability by area, p<0.001).

## Key Findings
- Demographics: Aged 25–44 (61.9%), married (46.7%), senior high educated (34.2%); KMA residence (38.1%).
- Economic: Mean income 187 GHS (38.4% ≤100 GHS); 9.81 work hours; challenges: price increases (55.0%), competition (29.1%).
- Social Capital: Mean 2.68/5; family support 3.24/5; gaps in protection (77.4%), childcare (50.3%); networks mean 10.5 contacts.
- Well-being: Mean 3.72/5 (83.4% high/very high); life satisfaction 4.42/10; correlates with social capital (r=0.641).
- Health/Safety: Malaria (43.9%); insurance 79.4%; poor air quality (2.90/5), noise (2.31/5).
- Vulnerability: Mean 2.29/5; Asokwa highest (3.46/5); low-income higher instability (3.79/5).
- Transportation: Walking (34.1%), public (6%); moderate commutes (56.0%) yield higher income (205 GHS).
- Clusters: 4 groups; vulnerable (12.8%, low income 74 GHS, well-being 2.37/5) needs urgent support.
- Policy: Financial inclusion (82.4% prefer), training (52.8%); target Asokwa for protection/childcare.



## How to Reproduce the Analysis
### Requirements
- R (version 4.0 or higher)
- RStudio
- R packages: tidyverse, ggplot2, dplyr, FactoMineR (PCA), cluster (k-means), corrplot

### Steps
1. Clone this repository.
2. Open `analysis.Rmd` in RStudio.
3. Install required packages if not already installed (e.g., `install.packages(c("tidyverse", "FactoMineR", "cluster"))`).
4. Knit the R Markdown file to generate the HTML report.
Data not included due to confidentiality. Please contact me for collaboration requests.

## Repository Structure
├── analysis.Rmd         # R Markdown source file  
├── analysis.html        # Knitted HTML report  
├── figures/             # Plots and visualizations  
├── README.md            # Project description  

## License / Citation
This project is for academic and research purposes. Please cite appropriately if referenced, e.g., Sei, Lawrence. (2025). WISER Project Ghana: How Does Social Capital Contribute to Well-Being in Times of Economic Challenges? Target Group: Street Vendors and Hawkers (Only Women): Exploratory Data Analysis.
