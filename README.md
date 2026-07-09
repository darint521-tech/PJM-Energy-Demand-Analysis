# PJM Regional Grid Electricity Demand & Temperature Analysis
An exploratory data analysis (EDA) evaluating the relationship between temperature and electricity demand.

## Project Overview
In this project, I will perform an exploratory data analysis (EDA) to investigate the relationship between temperature and electricity demand in New York. The datasets consist of time-series measurements of ambient temperature (°C) and electricity demand (MW). These variables are continuous and are expected to exhibit a relationship due to the increased use of cooling systems during periods of high temperature.

## Hypothesis
I hypothesize that electricity demand will increase as temperature rises, reflecting higher energy consumption from air conditioning and other cooling technologies. Through statistical analysis and visualization, I aim to quantify this relationship and assess the strength of the dependence between the two variables.

## Tech Stack & Environment
This analysis was built entirely within Google Colab using a standard data science environment.
* **Language:** Python 3
* **Libraries:** 
  * `pandas` & `numpy` (Data wrangling and time-series sorting)
  * `scipy.stats` (Statistical testing and correlation analysis)
  * `matplotlib.pyplot` (Data visualization and plotting)

## Data Source
* **Data Metrics:** Hourly Ambient Temperature (°C) and Grid Electricity Demand (MW).
* **Context:** Continuous historical time-series measurements pulled from the PJM Interconnection grid zone database.

## Code & Analysis Steps
The project workflow inside the notebook follows these specific phases:
1. **Data Cleaning:** Importing the CSV datasets, checking for missing time stamps, and formatting column types.
2. **Data Processing:** Aligning the temperature readings with the electricity demand metrics across continuous dates.
3. **Exploratory Plotting:** Generating scatter plots and line charts to visually map out how demand behaves when temperatures spike.
4. **Statistical Testing:** Running correlation algorithms using SciPy to find the mathematical dependence between the two metrics.

## Conclusion & Findings
The data confirmed my hypothesis, revealing a strong non-linear relationship between the variables. Once ambient temperatures exceeded 20–22°C, grid electricity demand accelerated sharply to handle regional cooling loads. The statistical analysis showed a high correlation during these heat spikes, indicating that temperature is a critical predictable driver of infrastructure load during summer months.


