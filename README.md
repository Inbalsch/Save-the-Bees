
# 🐝 Save The Bees — Varroa Mites  #1 Enemy! (Dashboard)

## 📊 Overview

This Tableau dashboard explores the impact of **Varroa mite infestations** on honey bee colony losses across the United States.
Using data from the [`Save the Honey Bees` dataset on Kaggle](https://www.kaggle.com/datasets/m000sey/save-the-honey-bees/data), the analysis identifies Varroa mites as the **leading cause of colony decline**, compares their prevalence to other causes, and visualizes geographic and temporal trends.

---

## 🎯 Key Insights

* **Varroa mites are the #1 reported cause** of colony loss, averaging the highest percentage among all reported causes.
* **Positive correlation** between Varroa mite % and colony loss %, supported by scatter plots and trend lines.
* Geographic heatmaps show that **Varroa infestation is widespread** across the U.S., not limited to a few states.
* Top-loss states (e.g., Arizona, New Mexico, Kansas) show **Varroa dominance** in cause breakdowns.
* Other causes (pesticides, diseases, weather) contribute to losses but have **weaker statistical relationships** with % Lost compared to Varroa.

---

## 📂 Files in This Repository

* **`varroa_mites_dashboard.twbx`** — Packaged Tableau workbook containing:

  * Cause contribution bar chart
  * Time-series trend comparison (Varroa % vs Loss %)
  * Correlation scatter plots
  * State-level heatmaps
  * Top-loss states cause breakdown
  * Comparative correlation chart
* **`save_the_bees(excel).xlsx`** *(optional)* — Source dataset.
* **`README.md`** — Documentation for the project.

---

## 📥 How to Use

1. **Download** the `.twbx` file from this repository.
2. Open it in **Tableau Desktop** or **Tableau Public** (free).
3. Interact with filters and hover over marks to explore insights.

---

## 📊 Dashboard Story

The dashboard is designed as a **six-visual narrative**:

1. **Cause Contribution** — Highlights Varroa as the largest cause.
2. **Time Trends** — Shows Varroa % moving in sync with Loss % over time.
3. **Correlation View** — Scatter plot + R² proves positive relationship.
4. **Geographic Spread** — Heatmap of Varroa % by state.
5. **Top-Loss States Breakdown** — Stacked bars showing Varroa dominance.
6. **Correlation Comparison** — Bar chart ranking causes by correlation with % Lost.

---

## 🛠 Tools & Technologies

This project used a mix of tools for **data preparation, analysis, and visualization**:

* **Python** — Data cleaning, transformation, and exploratory analysis.
* **SQL** — Querying, aggregating, and filtering the dataset.
* **Excel** — Additional data preprocessing and quick checks.
* **Tableau Desktop / Tableau Public** — Final visualization and storytelling.

---

## 📜 Data Source

Dataset: [`Save the Honey Bees` — Kaggle](https://www.kaggle.com/datasets/m000sey/save-the-honey-bees/data)
Contains bee colony loss data across U.S. states, broken down by cause, year, and season.



