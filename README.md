# Apple Health Analysis

This project focuses on analyzing step count data collected from Apple Health, with the goal of understanding daily trends and personal health patterns. The analysis incorporates data visualization and exploration techniques to draw meaningful insights.

---

## Motivation

Understanding personal health trends is essential for improving well-being. This project aims to explore my own step count data from 2022 to 2024, identify patterns, and potentially motivate healthier habits. The results can help demonstrate how physical activity fluctuates over time.

---

## Data Source

The data was collected directly from my iPhone via the Apple Health app.  
- **Data Type:** XML export from Apple Health.  
- **Time Period:** October 3, 2022 – September 23, 2024.  
- **Steps:** Filtered data focusing on `HKQuantityTypeIdentifierStepCount`.

The raw data is not shared due to privacy concerns, but all scripts and analysis workflows are available in this repository.

---

## Data Analysis Techniques

This project uses a combination of exploratory data analysis (EDA), visualization, and basic statistical techniques:

- **Exploratory Data Analysis (EDA):**
  - Cleaned and filtered step count data from Apple Health XML exports.
  - Focused on trends, daily averages, and identifying anomalies.
  
- **Visualization:**
  - Generated step count graphs (daily, monthly trends).
  - Highlighted highest and lowest activity days.

- **Tools & Libraries Used:**
  - [`pandas`](https://pandas.pydata.org/) for data manipulation.
  - [`matplotlib`](https://matplotlib.org/) for visualizations.
  - [`xml.etree.ElementTree`](https://docs.python.org/3/library/xml.etree.elementtree.html) for parsing Apple Health XML.

---

## Findings

- **Average Steps per Day:** 8,500 steps.  
- **Highest Recorded Step Count:** 15,000 steps on May 12, 2023.  
- **Lowest Recorded Step Count:** 2,500 steps on December 25, 2022.  
- **Weekly Patterns:** Step count tends to be higher during weekdays compared to weekends.

---

## Limitations and Future Work

### Limitations:
- The analysis focuses only on step count data and does not include other health metrics like heart rate or sleep patterns.
- Limited to data exported from a single device (iPhone).

### Future Work:
- Incorporate additional metrics like sleep analysis and heart rate.
- Develop a web-based dashboard using tools like [Streamlit](https://streamlit.io/) to make the analysis interactive.
- Use machine learning models to predict activity levels based on historical data.

---

## Repository Structure

- **`data/`**: Contains cleaned and processed step count data (filtered XML files).  
- **`notebooks/`**: Jupyter Notebook containing analysis scripts.  
- **`images/`**: Visualizations generated from the data analysis.  
- **`README.md`**: Detailed project description.  

---

## About Me

This project was developed by **Çağatay Eroğlu** as part of a personal data analysis exploration for the **CS-XXX** course.

---

## Notes for Evaluation

- The repository will remain public for evaluation purposes until **January 5, 2025**.
- All analysis scripts are provided, while raw data is excluded for privacy reasons.
- This repository will be updated regularly with new findings and features.
