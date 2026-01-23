# Lab 01 — Variability & Outliers

## 🎯 Objective
To analyze data dispersion and identify outliers using box plots, summary statistics, and visualization techniques in Python.

---

## 🧩 Topics Covered
- Measures of dispersion (IQR, Quartiles, Five Point Summary)
- Box plots
- Outlier detection
- Variability across numeric features
- Visual comparison using Seaborn & Matplotlib

---

## 🛠 Libraries Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 📁 Files Included
- `lab1_variability.ipynb` — Main notebook containing all code and outputs
- `./screenshots/` — Contains graphs & visualizations generated during execution

---

## 📊 Tasks Overview

This lab involves the following tasks based on the provided instructions :contentReference[oaicite:1]{index=1}:

1. Creating a box plot for a simple numeric dataset.
2. Analyzing calories dataset (Vanilla ice cream) for:
   - Mean, Median, Mode
   - Five-point summary
   - Outliers
3. Detecting outliers in `Lab1_Tips.csv` using Pandas boxplot.
4. Group-wise boxplot visualization for total bill by day.
5. Using Seaborn for enhanced boxplots.
6. Variability analysis on `Lab1_StudentsPerformance.csv` dataset:
   - Selecting numeric features
   - Generating summary statistics
   - Plotting variability using Seaborn
7. Exercise:
   - Apply variability analysis to `tips.csv` dataset
   - Compute summary statistics
   - Boxplot visualization

---

## 📝 Key Observations
- Box plots provide an effective visual summary of central tendency and dispersion.
- Whiskers indicate spread and potential outliers.
- Outliers appear as individual points beyond whiskers.
- Different numeric fields may show different levels of variability (e.g., `total_bill` > `tip` > `size`).
- Variability analysis helps in understanding dataset behavior before modeling.

---

## 📦 Datasets Required
Place the following datasets in the same folder:

- `Lab1_Tips.csv`
- `Lab1_StudentsPerformance.csv`
- `Lab1_Vanilla.csv`

If not provided, use equivalent public Kaggle datasets.

---

## 🚀 How to Run the Notebook
From the root folder:

```bash
pip install -r ../../requirements.txt
jupyter notebook lab01_variability.ipynb

