# Student-Teacher Ratio Analysis (2021–2025)

**Author:** Zin Min Thnat  
**Date:** 2025-04-18

---

## Project Overview

This project analyzes student-teacher ratios across different school districts and statewide totals from 2021 to 2025. The goal is to visualize trends in ratios and compare enrollment numbers to teacher counts over the years.

---

## Files in this Repository

- `Student Teacher Ratio by District 2025.csv` — District-level student-teacher ratio data.
- `Student Teacher Ratio by state total.csv` — Statewide enrollment and teacher counts.
- `Final_Project.Rmd` — R Markdown file containing the analysis, code, and visualizations.
- (Optional) `Final_Project.html` — Knit output for easy web viewing.

---

## Key Features

- **Data Transformation:** Uses `tidyverse` functions like `pivot_longer` to reshape data for plotting.
- **Visualizations:**
  - Line plot showing student-teacher ratios by district across years.
  - Stacked bar chart comparing enrollment and teacher percentages by year.
- **Reproducible Analysis:** All code is included in the R Markdown document.

---

## How to Run

1. Make sure you have R and RStudio installed.
2. Install necessary packages by running:

```r
install.packages(c("tidyverse", "stringr"))
