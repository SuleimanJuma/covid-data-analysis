# covid-data-analysis


# COVID-19 Data Analysis Project

This project explores the global impact of COVID-19 using data from [Our World in Data](https://ourworldindata.org/coronavirus). It visualizes trends in cases, deaths, vaccination progress, and examines how socioeconomic factors such as GDP per capita, population, and age affect death rates and reporting.

---

## 🎯 Project Objectives

- Analyze global COVID-19 trends in terms of daily new cases and deaths.
- Examine relationships between COVID-19 indicators and socioeconomic variables.
- Visualize vaccination progress across countries.
- Investigate possible correlations between:
  - GDP per capita vs. COVID-19 death rate
  - Median age vs. COVID-19 death rate
  - Population size vs. total reported cases
  - HDI vs. testing/reporting levels

---

## 🧰 Tools & Libraries Used

- **Python 3.10+**
- **Jupyter Notebook**
- **Pandas** for data manipulation
- **Matplotlib** and **Seaborn** for data visualization
- **NumPy** for numerical operations
- **CSV** dataset from [Our World in Data](https://ourworldindata.org/coronavirus)

---

## 🚀 How to Run / View the Project

1. Clone this repository or download it as a ZIP.
2. Open `COVID19_Data_Analysis_Project.ipynb` in Jupyter Notebook or VS Code (with Jupyter extension).
3. Make sure the dataset `owid-covid-data.csv` is in the same folder.
4. Run all the cells to generate the visualizations and insights.

Alternatively, you can view the markdown files for summarized observations:

- `covid19case trends.md`
- `death_rates_observations.md`
- `Deathrate_vs_gdp.md`
- `deathrate_vs_medianage.md`
- `newdaily covid19 cases.md`

---

## 💡 Insights & Reflections

- Wealthier countries (higher GDP per capita) tend to report lower death rates — possibly due to better healthcare infrastructure.
- Countries with older populations (higher median age) show higher mortality rates, highlighting vulnerability among elderly.
- Population size correlates with case totals, but not always proportionally — some small countries had very high per capita cases.
- Countries with higher HDI often had better reporting and testing — shown in higher cases per million due to more widespread surveillance.
- Vaccination trends vary widely — early adopters generally had lower death spikes after rollout.

This project provided a meaningful way to analyze global public health data, blending real-world issues with data science and visualization.

---

## 📂 Files in This Repo

| File Name                        | Description                                                 |
| ------------------------------- | ----------------------------------------------------------- |
| `COVID19_Data_Analysis_Project.ipynb` | Main analysis notebook with full code and charts.           |
| `owid-covid-data.csv`           | COVID-19 dataset used for analysis.                         |
| `covid19case trends.md`         | Markdown notes on new case trends and observations.         |
| `newdaily covid19 cases.md`     | Daily trends in reported cases.                             |
| `death_rates_observations.md`   | Summarized insights on death rates.                         |
| `Deathrate_vs_gdp.md`           | Observations from GDP vs. death rate plots.                 |
| `deathrate_vs_medianage.md`     | Observations from age vs. death rate comparisons.           |

---

## 👤 Author

Suleiman Juma 

---

