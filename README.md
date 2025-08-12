# CGPA Prediction Project – Final Report

## Overview
This repository contains the code, report, and presentation for our **joint final project** in the course **Introduction to Data Science (382.1.2601)**.  
The project explores and predicts students' cumulative GPA (CGPA) based on academic, demographic, and behavioral features, using data from Computer Science and Engineering students in Bangladesh.  
The analysis and modeling are implemented in **R**, documented in `Final_project.Rmd`.

**Project authors (team project):**  
Noam Yehoshua  
Bar Elhayani  
Dotan Katz  
Oran Kedem

---

## Project Structure
```
project-root/
├── Project Proposal/
│   └── proposal.pdf
├── Final Project/
│   ├── final report.pdf
│   ├── Final_Presentation.pdf
│   └── Final_project.Rmd
└── README.md
```

---

## How to Reproduce

1. **Clone this repository**
   ```bash
   git clone <repo-url>
   ```

2. **Download the dataset**
   - **Main dataset (used in the final model):**  
     https://data.mendeley.com/datasets/dc3797vf3t/1  
     Save it in the **project root** (same level as this README) as:  
     `Students_Performance_data_set.xlsx`

3. **Open and run the analysis**
   - Open `Final Project/Final_project.Rmd` in **RStudio** and knit/run all chunks.  
   - If your working directory is not the repo root, set it with `setwd('..')` or adjust the dataset path accordingly.

---

## Required R Packages
Make sure these packages are installed before running:
```
knitr
tidyverse
broom
htmltools
readxl
tidymodels
rsample
dplyr
yardstick
ranger
ggplot2
reshape2
tibble
gridExtra
janitor
corrplot
```

Install in R with:
```r
install.packages(c("knitr", "tidyverse", "broom", "htmltools", "readxl",
                   "tidymodels", "rsample", "dplyr", "yardstick", "ranger",
                   "ggplot2", "reshape2", "tibble", "gridExtra", "janitor", "corrplot"))
```

---

## Notes
- The dataset is **publicly available online** and therefore not included in this repository.  
- Full reproduction requires placing the dataset exactly as described above.  
- This is a **team project** completed as part of the course **Introduction to Data Science (Spring 2024–2025)**.
