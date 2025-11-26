# Econometric-Analysis-of-Sesamum-Sesame-Crop-Production-in-India 🌾

## Project Description

A comprehensive data science and econometric project analyzing the **Sesamum (Sesame)** production function across Indian districts (2017).

The study involves **integrating and cleaning multiple district-level datasets** (crop output, core inputs, rainfall, and soil quality) to estimate and compare **Cobb-Douglas** and **Quadratic** production models. The primary goal is to evaluate input efficiency, returns to scale, and the impact of environmental factors on production.

---

## Key Analytical Focus

This project demonstrates expertise in advanced econometric modeling and data preparation by specifically addressing:

* **Data Integration:** Merging and cleaning diverse data sources (agriculture, weather, soil) based on district codes.
* **Model Comparison:** Rationale for preferring the **Quadratic Model** over Cobb-Douglas (due to its ability to test non-linear effects and diminishing returns).
* **Diminishing Returns:** Statistical testing of the **Law of Diminishing Marginal Returns** for key inputs (e.g., Area and Nitrogen application).
* **Input Complementarity:** Evaluation of the synergistic effect of **Irrigation** and **Fertilizer** (using interaction terms).
* **Regional Heterogeneity:** Testing for significant differences in the production function across various **RBI-defined regions** in India.

---

## ⚙️ Technical Stack

* **Language:** Python
* **Libraries:** `pandas`, `numpy`, **`statsmodels`** (for OLS regression and hypothesis testing), `matplotlib`.
* **Environment:** Jupyter Notebook (`Main.ipynb`).

---

## 📁 Repository Structure

| File/Folder | Description |
| :--- | :--- |
| `Main.ipynb` | Contains all Python code for data merging, model specification, estimation, hypothesis testing, and result interpretation. |
| `Project_ECO221_2025.pdf` | Original project brief detailing the required econometric tasks. |
| `data/` | **Data Folder:** Contains all raw and processed CSV files used for the analysis, demonstrating data management skills. |
| ├── `ECO221_Project_2025_Final.csv` | Primary data on crop production and input consumption. |
| ├── `RF_DistrictWise_ECO221_2025.csv` | District-wise Rainfall data. |
| ├── `Salinity_Alkalinity_ECO221_2025.csv`| District-wise Soil Quality (Salinity/Alkalinity) data. |
| └── `sesamum_data_final...csv` | The final merged dataset used for modeling. |

***
