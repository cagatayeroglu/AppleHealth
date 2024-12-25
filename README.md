## TABLE OF CONTENT

- [data](https://github.com/cagatayeroglu/AppleHealth/tree/main/data): Contains cleaned and processed step count data (filtered XML files).  
- [`AppleHealth.ipynb`](https://github.com/cagatayeroglu/AppleHealth/blob/main/AppleHealth.ipynb): Jupyter Notebook containing analysis scripts.  
- [`AppleHealth_PP.pptx`](https://github.com/cagatayeroglu/AppleHealth/blob/main/slides.pptx): Slides for visualizations that generated from the data analysis.  
- [`README.md`](https://github.com/cagatayeroglu/AppleHealth/blob/main/README.md): Detailed project description.  

---


# Apple Health Analysis

This project focuses on analyzing step count data collected from Apple Health, with the goal of understanding daily trends and personal health patterns. The analysis incorporates data visualization and exploration techniques to draw meaningful insights. While aiming to explain the affect of Sabancı Campus to daily activity, we exclude the outliers to get the pure data that will show to affect.

---

## Motivation

Understanding personal health trends is essential for improving well-being. This project aims to explore my own step count data from 2022 to 2024, identify patterns during different terms and potentially understand the patterns. The results can help demonstrate how physical activity fluctuates over time during academic term due to campus mobility. 

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

- **Activity During School Year:**  
  The data indicates an increase in daily step count during the school year, likely due to the large campus and frequent walking between classes. Average daily steps during the school year exceeded those recorded in other periods.

- **Lower Activity During Summer:**  
  A noticeable decrease in step count was observed during summer months. Despite certain outlier events, such as summer internships, overall activity levels were lower compared to the school term.

- **Impact of Outliers:**  
  Outlier days, such as those during summer internships, temporarily increased daily step counts but were insufficient to offset the overall decline in activity during the summer.

- **Weekly Patterns:**  
  Step count data shows higher activity levels during weekdays compared to weekends, reflecting routine class schedules and campus activities.

These findings highlight the significant impact of environment and routine on physical activity levels, with structured environments like school contributing positively to daily step counts.

For the detailed findings and analysis : [`AppleHealth.ipynb`](https://github.com/cagatayeroglu/AppleHealth/blob/main/AppleHealth.ipynb)

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


## About Me

This project was developed by **Çağatay Eroğlu** as part of a personal data analysis exploration for the **DSA210** course.

---


