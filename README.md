# Car Emissions Analysis

## Overview  
This project explores vehicle emissions data to understand how fuel type, mileage, and engine characteristics influence CO₂ output. Using Python-based exploratory data analysis and visualization, the project identifies trends across vehicle categories and highlights which factors contribute most to emissions levels.

The analysis supports data-driven insights into environmental impact, efficiency patterns, and opportunities for reducing emissions across vehicle types.

---

## Data Description  
The dataset includes key vehicle attributes such as:

- **Make** – manufacturer  
- **Model** – specific vehicle name  
- **Fuel Type** – gasoline, diesel, electric, hybrid, etc.  
- **Transmission** – automatic, manual, CVT  
- **Cylinders** – number of engine cylinders  
- **Engine Size** – engine displacement  
- **Fuel Consumption** – city, highway, and combined values  
- **CO₂ Emissions** – grams of CO₂ emitted per kilometer  

These variables allow comparison across vehicle classes and provide insights into efficiency and sustainability.

---

## Methods  

### 1. Data Cleaning  
- Checked for null or incorrect values  
- Standardized column formats  
- Converted numeric fields to appropriate types  
- Removed invalid or extreme outliers  

### 2. Exploratory Data Analysis  
The notebook includes visualizations such as:

- **Bar Charts by Fuel Type**  
  Shows average CO₂ emissions by fuel category.

- **Scatterplots of Engine Size vs. Emissions**  
  Highlights relationships between power and environmental impact.

- **Boxplots by Vehicle Class**  
  Illustrates emission ranges across different vehicle styles.

- **Correlation Heatmap**  
  Examines relationships among engine size, consumption, and emissions.

### 3. Feature Engineering  
Derived fields include:

- **Emission Category** (low, medium, high)  
- **Fuel Efficiency Ratios**  
- **Class-based averages**  

These features help interpret emissions patterns more clearly.

---

## Key Insights  

- Gasoline vehicles generally have higher CO₂ emissions compared to electric and hybrid models.  
- Larger engines (higher liters and more cylinders) correlate strongly with increased emissions.  
- Certain vehicle classes show high variability, indicating inconsistent efficiency across models.  
- Fuel consumption metrics are strong predictors of emissions performance.  

---

## Requirements  

Install necessary libraries:

```bash
pip install pandas matplotlib seaborn numpy
```

---

## How to Use  

1. Open the Jupyter notebook included in the repository.  
2. Load the emissions dataset.  
3. Run preprocessing and cleaning steps.  
4. Generate visualizations to explore emissions across fuel types and vehicle features.  
5. Interpret the insights for environmental analysis and reporting.

---

## Future Improvements  

- Add machine learning models to predict emissions based on vehicle features.  
- Incorporate manufacturer-level comparisons across multiple years.  
- Build a dashboard for interactive filtering by fuel type, engine size, and class.  
- Add geographic mapping using region or country metadata (if available).

---

## Files Included  

- `Car_Emissions_Analysis.ipynb` – full analysis workflow  
- `Car_Emissions.csv` – emissions dataset  
- `README.md` – project documentation  
