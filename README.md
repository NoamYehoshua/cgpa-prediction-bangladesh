# CGPA Prediction Project – Final Report

## Overview
This repository contains the code and files used for analyzing and predicting students' CGPA based on academic, demographic, and behavioral features. The project is built in R and documented in the file `Final_project.Rmd`.

---

## How to Reproduce

1. **Clone this repository**
2. **Download the following datasets:**

   - **Main dataset (used in the final model):**  
     https://data.mendeley.com/datasets/dc3797vf3t/1  
     Save as: `Students_Performance_data_set.xlsx` in the project root.

   - **Additional datasets used in exploratory comparison:**  
     - [xAPI-Edu-Data](https://www.kaggle.com/datasets/aljarah/xAPI-Edu-Data) → save to `research_data/xAPI-Edu-Data.csv`  
     - [Students Performance in Exams](https://www.kaggle.com/datasets/spscientist/students-performance-in-exams) → save to `research_data/data6article.csv`  
     - [Higher Education Students Performance Evaluation](https://archive.ics.uci.edu/dataset/856/higher%2Beducation%2Bstudents%2Bperformance%2Bevaluation) → save to `research_data/HigherEducationStudentsPerformanceEvaluation.csv`

3. **Folder structure:**
   ```
   project-root/
   ├── Final_project.Rmd
   ├── Students_Performance_data_set.xlsx
   └── research_data/
       ├── xAPI-Edu-Data.csv
       ├── data6article.csv
       └── HigherEducationStudentsPerformanceEvaluation.csv
   ```

4. **Open `Final_project.Rmd` in RStudio and knit/run all chunks.**

---

## Required R Packages

Please make sure the following R libraries are installed:

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

You can install them using `install.packages()` as needed.

---

## Notes

- The datasets used in this project are publicly available online and therefore not included directly in this repository. Links are provided above.
- All analyses can be reproduced by following the instructions above.
