# Exploratory Data Analysis (EDA) Project - Online Retail Sales Analysis and Customer Insights

A comprehensive Exploratory Data Analysis (EDA) repository dedicated to uncovering patterns, detecting anomalies, testing hypotheses, and checking assumptions within the dataset using summary statistics and graphical representations.

## 📌 Project Overview
This project demonstrates standard data science workflows for inspecting and cleaning data, understanding underlying distributions, and identifying critical relationships between variables before applying machine learning models.

---

## 📂 Repository Structure
```text
├── eda.ipynb          # Main Jupyter Notebook containing the analysis, visualizations, and insights
└── README.md          # Project documentation (this file)
```

## 🛠️ Tech Stack & Libraries
The analysis is built using the core Python data science ecosystem:
* **Data Manipulation:** `pandas`, `numpy`
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook

---

## 📊 Core Analysis Workflow
The notebook follows a structured data science pipeline:

1. **Data Ingestion & Inspection:** Loading the dataset, checking shape, data types, and structural properties (`.info()`, `.describe()`).
2. **Data Cleaning:** * Handling missing values (imputation or removal).
   * Detecting and dropping duplicate entries.
   * Correcting inconsistent data types.
3. **Univariate Analysis:** Analyzing individual feature distributions using histograms, KDE plots, and box plots to spot outliers.
4. **Bivariate & Multivariate Analysis:** Utilizing scatter plots, pair plots, and correlation heatmaps to uncover interactions between variables.
5. **Key Insights Summary:** Documenting actionable takeaways driven by the visualizations.
