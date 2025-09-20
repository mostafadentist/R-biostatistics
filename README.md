# Biostatistics Analysis Notebook

This repository contains a comprehensive **R-based Jupyter Notebook** (`R_Biostatistics_.ipynb`) that provides examples of statistical methods commonly used in biostatistics and clinical data analysis. It includes sections on descriptive statistics, visualization, hypothesis testing, survival analysis, and more.

---

## Features

### 1. **Descriptive Statistics**
- Examines the central tendency and variability of blood pressure data.
- Calculates **mean**, **median**, and **standard deviation**.
- Demonstrates the use of R functions like `mean()`, `median()`, and `sd()`.

---

### 2. **Data Visualization**
- Visualizes blood pressure data using:
  - **Histograms** for distribution analysis.
  - **Boxplots** for spread, quartiles, and outliers.
  - **Density plots** for probability distribution.
- All visuals are created using the `ggplot2` library.

---

### 3. **Hypothesis Testing**
- **One-sample t-test:** Tests whether the mean blood pressure is significantly different from 120 mmHg.
- **Two-sample t-test:** Compares blood pressure between treatment and control groups.
- Provides statistical interpretations, including **p-values** and **confidence intervals**.

---

### 4. **Categorical Data Analysis**
- Performs a **Chi-square test** to evaluate the association between treatment groups and categorical outcomes.
- Visualizes results using stacked bar plots with `ggplot2`.

---

### 5. **Survival Analysis**
- Simulates survival data and performs **Kaplan–Meier estimation**.
- Includes survival curves with confidence intervals and p-value from **log-rank tests**.
- Uses the `survival` and `survminer` R packages.

---

## Requirements

- **Jupyter Notebook** with R kernel.
- R packages:
  - `ggplot2`
  - `survival`
  - `survminer`

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/biostatistics-analysis.git
   cd biostatistics-analysis
