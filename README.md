# Is COVID-19 Impact Uniform Across Countries?

This project explores how the COVID-19 pandemic affected different countries in terms of active cases and death rates, using data sourced from the **Johns Hopkins University COVID-19 Data Repository**.

---

## Project Overview

While many countries reported similar numbers of active COVID-19 cases, their death rates varied significantly. This project investigates these variations to understand the roles of healthcare systems, government interventions, and other factors in managing the pandemic.

**Main Question:**  
What helped some countries manage the COVID-19 crisis better than others?

---

## Dataset Information

- **Source:** Johns Hopkins University COVID-19 Data Repository  
- **Size:** 1.6 GB (Millions of records, 2020–2023)  
- **Attributes Used:**  
  - Country  
  - Confirmed Cases  
  - Active Cases  
  - Deaths  
  - Death Rate (calculated)

This dataset meets the criteria for **Big Data** with its:
- **Volume** – millions of records  
- **Velocity** – daily updates  
- **Variety** – wide range of attributes across countries and time

---

## Data Cleaning & Preparation

- Filtered countries with incomplete data  
- Estimated missing values using interpolation  
- Created new calculated column: `Death Rate (%) = (Deaths / Confirmed Cases) × 100`  
- Normalized active cases using logarithmic scaling  
- Focused on 2023 data to streamline analysis

---

## Visualizations

1. **Bar Chart** – Confirmed cases across countries  
2. **Scatter Plot** – Active cases vs death rates  
3. **Bubble Chart** – Combined death rate, active cases, and case magnitude (main visualization)

The final dashboard was created using **Power BI** for interactivity and clarity.

---

## Tools & Libraries Used

- **Python (Jupyter Notebook, Google Colab):**  
  - `pandas`, `numpy`, `matplotlib`

- **Power BI:**  
  - For dynamic bubble chart visualization

---

## Key Insights

- COVID-19’s impact was **not uniform**—some countries with fewer active cases had high death rates.
- Early interventions like **lockdowns, mass testing, and vaccinations** played a crucial role.
- **Healthcare infrastructure** made a significant difference in outcomes.

---

## Contributors

- **Nikhil Kumar** – Dashboard design in Power BI and key analysis insights  
- **Venga Vamsi Krishna Maanam** –  Data cleaning, exploration, and report writing  

---

## Files in this Repository

- `DataVisulaisation_ass.ipynb` – The Jupyter Notebook with all code and visualizations  
- `finalreport(DV).pdf` – A 1-page project summary and visual analysis  

---

## References

- [Johns Hopkins COVID-19 Data Repository](https://gi)
