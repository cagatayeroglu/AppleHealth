# Apple Health Analysis

This project focuses on analyzing step count data collected from Apple Health, with the goal of understanding daily trends and personal health patterns. The analysis incorporates data visualization and exploration techniques to draw meaningful insights.

---

## Motivation

Understanding personal health trends is essential for improving well-being. This project aims to explore my own step count data from 2022 to 2024, identify patterns during different terms and potentially understand the patterns. The results can help demonstrate how physical activity fluctuates over time.

---

## Data Source

The data was collected directly from my iPhone via the Apple Health app.  
- **Data Type:** XML export from Apple Health.  
- **Time Period:** October 3, 2022 – September 23, 2024.  
- **Steps:** Filtered data focusing on `HKQuantityTypeIdentifierStepCount`.

---

## Data Analysis Techniques

This project uses a combination of exploratory data analysis (EDA), visualization, and basic statistical techniques:

- **Exploratory Data Analysis (EDA):**
  - Cleaned and filtered step count data from Apple Health XML exports.
  - Focused on trends, daily averages, and identifying anomalies.
  
- **Visualization:**
  - Generated step count graphs, box plots (daily, monthly trends).
  - Highlighted highest and lowest activity days.

- **Tools & Libraries Used:**
  - [`pandas`](https://pandas.pydata.org/) for data manipulation.
  - [`matplotlib`](https://matplotlib.org/) for visualizations.
  - [`xml.etree.ElementTree`](https://docs.python.org/3/library/xml.etree.elementtree.html) for parsing Apple Health XML.

---

## Findings

- **Average Steps per Day:** Calculated from filtered data in the notebook.  
- **Highest Recorded Step Count:** Derived from the analysis (refer to notebook).  
- **Lowest Recorded Step Count:** Derived from the analysis (refer to notebook).  
- **Weekly Patterns:** Step count variations across weekdays and weekends.

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

- [data](https://github.com/cagatayeroglu/AppleHealth/tree/main/data): Contains cleaned and processed step count data (filtered XML files).  
- [`AppleHealth.ipynb`](https://github.com/cagatayeroglu/AppleHealth/blob/main/AppleHealth.ipynb): Jupyter Notebook containing analysis scripts.  
- [`slides.pptx`](https://github.com/cagatayeroglu/AppleHealth/blob/main/slides.pptx): Slides for visualizations that generated from the data analysis.  
- [`README.md`](https://github.com/cagatayeroglu/AppleHealth/blob/main/README.md): Detailed project description.  

---

## About Me

This project was developed by **Çağatay Eroğlu** as part of a personal data analysis exploration for the **DSA210** course.

---


