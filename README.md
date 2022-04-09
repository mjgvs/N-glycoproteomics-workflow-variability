# Technical report: variability in glycopeptide workflow

This repository contains files used in the creation of a report on the variability in glycopeptide intensity. The report describes joint work by Frania J. Zuñiga-Bañuelos and Maarten van Schaik, PhD candidates in the EU-funded programme IMforFUTURE (Innovative training in methods for future data).

The report can be read here: [N-glycoproteomics-workflow-variability/](https://mjgvs.github.io/N-glycoproteomics-workflow-variability/).

For the statistical part in the report, the following software was used:

- `R` version 3.6.3 (2020-02-29) 64-bit
- Tableau 2020.2

The following `R` packages were used:

- `Tidyverse` 1.3.0
- `readxl` 1.3.1
- `writexl` 1.3
- `ggplot2` 3.3.0
- `data.table` 1.12.8

The files are:

Data files:

- `/data/Fib_1.csv`-`Fib_4.csv`: The raw data.
- `/data/Fib_total_processed.csv`: Merged and pre-processed raw data. 
- `/data/Fib_total_processed.Rds`: Merged and pre-processed raw data in RDs form. 
- `/data/summaries/Fib_summary_AUC.xlsx`: Summary measures of N-glycopeptide intensities per replicate and mean, sd and CV of these.
- `/data/summaries/Fib_summary_count.xlsx`: Summary measures of N-glycopeptide counts, relative counts and presence indicators per replicate and mean, sd and CV of these.

Figures:
- `/Figures/`

Scripts
- `/scripts/R/N-glycopeptide Statistical Analysis.Rmd`: All `R` scripts. 
- `/scripts/Tableau/Fib_4_samples.twbx`: Tableau Packaged Workbook for visualisations. 

Blog post / report files:
- `index.Rmd` and `index.html`: Files to build the website for the report. 


