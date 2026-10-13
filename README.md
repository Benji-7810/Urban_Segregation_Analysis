# Urban Segregation Analysis: Social Housing and Socioeconomic Inequality in France

## Overview

This project investigates the relationship between social housing and socioeconomic segregation across major French urban areas.

Conducted as part of an academic study in urban economics, the analysis uses publicly available data from the French National Institute of Statistics and Economic Studies (INSEE).

Using Python, the project focuses on data processing, statistical indicator calculation, correlation analysis, and visualization to explore how the proportion of social housing relates to the socioeconomic composition of urban areas.

## Research Question

**To what extent is the proportion of social housing associated with socioeconomic segregation in French urban areas?**

The analysis explores potential relationships between social housing distribution, occupational categories, and socioeconomic homogeneity across urban areas.

## Objectives

The main objectives of this project are to:

- Process and organize socioeconomic datasets from INSEE.
- Calculate social housing rates across French urban areas.
- Compute socioeconomic homogeneity indicators.
- Explore correlations between social housing rates and segregation indicators.
- Analyze the distribution of socioeconomic and occupational categories.
- Generate statistical visualizations to identify patterns and relationships.
- Interpret the findings from an urban economics perspective.

## Technologies

| Technology | Purpose |
|---|---|
| Python 3.10 | Data processing and statistical analysis |
| Pandas | Data manipulation and aggregation |
| Matplotlib | Data visualization |
| INSEE Datasets | Official French socioeconomic and housing statistics |

## Project Structure

The repository is organized into the following directories:

**do/** — Python scripts for data processing and analysis.

- `calcule_de_taux.py` — Calculation of social housing rates.
- `calcule_homogeneite.py` — Calculation of socioeconomic homogeneity indicators.
- `main_code.py` — Main analysis and visualization script.

**inputs/** — Source and processed CSV datasets.

- `aire_urbaine.csv`
- `Logement_Total.csv`
- `Logement_sociaux.csv`
- `logements_sociaux_taux.csv`
- `indice_homogeneite_et_taux_social_par_AAV.csv`
- `population_metier.csv`

**outputs/** — Generated statistical visualizations.

- `correlation_logements_sociaux_segregation.png`
- `CS2_vs_logements_sociaux.png`
- `CS3_vs_logements_sociaux.png`
- Additional statistical figures.

**Additional documents**

- `Presentation.pdf` — Project presentation.
- `texte_eco.docx` — Written economic analysis.
- `README.md` — Project documentation.

## Installation

### 1. Clone the repository

Clone the project and navigate to its directory.

`git clone https://github.com/Benji-7810/Urban-Segregation-Analysis.git`

`cd Urban-Segregation-Analysis`

### 2. Install dependencies

Make sure Python 3.10 or a compatible version is installed.

Install the required Python libraries:

`pip install pandas matplotlib`

## Usage

Run the main analysis script:

`python do/main_code.py`

The script processes the datasets and generates statistical visualizations, which are saved in the `outputs/` directory.

## Methodology

The analysis follows four main stages.

### 1. Data Preparation

Import, process, and organize datasets containing information on social housing, employment categories, and French urban areas.

### 2. Statistical Indicator Calculation

Calculate social housing rates and socioeconomic homogeneity indicators to characterize the different urban areas.

### 3. Correlation Analysis

Explore statistical relationships between social housing proportions and socioeconomic segregation indicators.

### 4. Data Visualization

Generate graphs to identify patterns, compare urban areas, and support the interpretation of statistical results.

The analysis focuses on statistical associations and does not establish causal relationships.

## Results and Visualizations

The project generates visualizations examining the relationship between social housing and socioeconomic characteristics.

The main outputs include:

- Correlation plots comparing social housing rates with segregation indicators.
- Comparisons between social housing rates and occupational categories.
- Additional visualizations supporting the statistical analysis.

The complete economic interpretation is available in `texte_eco.docx`, while `Presentation.pdf` provides a summary of the study.

