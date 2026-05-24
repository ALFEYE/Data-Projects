# Winnipeg Weather Analysis (2015–2025)

##  Project Overview

This project analyzes how weather conditions in Winnipeg differ between high precipitation days and dry days using historical climate data from 2015 to 2025.

The goal is to identify patterns between precipitation levels and temperature, and explore how weather conditions change during wetter days.

---

##  Objective

* Compare **high precipitation days** vs **dry days**
* Analyze differences in:

  * Temperature
  * Weather variability
* Visualize relationships between precipitation and temperature

---

##  Dataset

The dataset contains daily climate observations for Winnipeg, including:

* Date
* Total precipitation (mm)
* Mean temperature (°C)
* Wind gust speed (km/h)

Data source: Canadian historical climate records (Environment Canada)

---

## Data Processing

The dataset was cleaned by:

* Removing missing values
* Selecting relevant weather variables
* Splitting data into:

  * High precipitation days (> 10 mm)
  * Dry days (0 mm)

---

##  Key Analysis

The analysis compares average weather conditions across different precipitation levels.

### Main findings:

* High precipitation days are associated with higher average temperatures
* Dry days tend to occur during colder conditions
* A visible relationship exists between precipitation and temperature patterns

---

##  Visualizations

The project includes:

* Bar chart comparing average temperatures
* Scatter plot showing precipitation vs temperature relationship

---

##  Tools Used

* Python
* Pandas
* Matplotlib
* Jupyter Notebook

---

##  Future Improvements

* Add seasonal analysis (winter vs summer patterns)
* Include snowfall-specific analysis when data is available
* Explore predictive modeling for precipitation trends

---

##  How to Run

1. Clone the repository
2. Install dependencies:

   ```bash
   pip install pandas matplotlib
   ```
3. Open `notebooks/analysis.ipynb`
4. Run all cells

---

## 👤 Author

Data analysis project built for learning and portfolio development.
