# 🚬 Smoking and Lung Cancer Dataset Analysis

This project investigates the relationship between smoking and lung cancer using simulated data. The analysis applies descriptive statistics, data cleaning, and chi-square testing in **R**, and is structured for reproducibility and clarity.

---

## 📂 Project Structure

- **`data/`**: Raw and cleaned datasets
- **`R/`**: Modular scripts for import, cleaning, analysis, and plotting
- **`reports/`**: Markdown summary reports (RMarkdown/Quarto)

---

## 📊 Variables

| Variable           | Description                          |
|--------------------|--------------------------------------|
| `Smoking_Status`   | Smoker (1) / Non-Smoker (2)          |
| `Lung_Cancer`      | Diagnosed: Yes (1) / No (2)          |
| `Age`              | Age in years                         |
| `Gender`           | Male (1) / Female (2)                |
| `Pollution_Exposure`| High (1) / Moderate (2) / Low (3)   |
| `Family_History`   | Yes (1) / No (2)                     |

---

## 📈 Methods

- **Chi-square test** for association between `Smoking_Status` and `Lung_Cancer`
- **Data cleaning** using `dplyr`
- **Visualization** with `ggplot2`

---

## 🧑‍💻 How to Run

```r
# Clone the repo
git clone https://github.com/YOUR_USERNAME/smoking-lung-cancer-analysis.git
cd smoking-lung-cancer-analysis

# Run R scripts in order
source("R/01_data_import.R")
source("R/02_data_cleaning.R")
source("R/03_chi_square_analysis.R")
