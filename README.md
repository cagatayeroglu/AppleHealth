# Health Data and Academic Intensity Analysis

**Author:** Cagatay Eroglu  
**Course:** DSA210 - Data Science and Applications  
**Student ID:** 32242  

---

## Motivation

How do daily habits change as academic workload increases? This project aims to examine personal physical health data to observe the impact of increasing academic intensity. By analyzing health metrics during different academic and non-academic phases, I hope to uncover patterns and correlations between academic schedules and physical health.

---

## Dataset

### **Source**  
- Data collected from Apple Health application in XML format.  

### **Description**  
- Metrics include **step count**, **flights climbed**, **energy burned**, and other physical health indicators.  
- Time-sensitive health data across multiple timelines.  
- Data spans from **2022-10-03** to **2024-09-23**, enabling a comparative analysis of health metrics across academic and non-academic periods.

### **Time Periods**  
1. **Academic Terms:**
   - **2022-10-03 to 2023-01-20**  
   - **2023-02-27 to 2023-06-11**  
   - **2023-10-02 to 2024-01-19**  
   - **2024-02-15 to 2024-06-11**

2. **Summer Breaks:**
   - **2023-06-11 to 2023-10-02**  
   - **2024-06-11 to 2024-09-24**

3. **Midterm Breaks:**
   - **2023-01-20 to 2023-02-27**  
   - **2024-01-19 to 2024-02-15**

4. **Internship Periods (Outliers):**
   - **2024-01-29 to 2024-02-09**  
   - **2024-07-04 to 2024-07-28**  
   - **2024-09-02 to 2024-09-20**

These internship periods were identified as outliers due to their deviation from regular academic or non-academic schedules, significantly influencing activity levels.

---

## Project Goals

1. **Analyze** how academic intensity affects physical activity and energy expenditure.  
2. **Identify trends** and correlations across different academic and non-academic phases.  
3. **Highlight deviations (outliers)** caused by internship periods.  
4. **Provide insights** into the relationship between academic workload and physical well-being.

---

## Methods and Techniques

### **1. Data Preprocessing**
- Parse XML data from Apple Health.  
- Clean and structure the dataset for analysis.  
- Handle missing or irrelevant data.  

### **2. Exploratory Data Analysis (EDA)**
- Use visualizations such as:
  - **Boxplots** to show distribution and variability in physical health metrics.  
  - **Scatter plots** to observe correlations between metrics like step count and energy burned.  
  - **Histograms** to analyze frequency distributions of activities.  
  - **Line charts** to observe trends over time.  
- Detect and analyze **outliers**, focusing on internship periods.  

### **3. Time-Series Analysis**
- Analyze data over time to observe long-term changes.  
- Identify seasonal patterns, anomalies, and deviations during internships.  

### **4. Comparative Analysis**
- Compare physical activity and energy expenditure across academic terms, breaks, and internship periods.  

### **5. Machine Learning (Optional)**
- Use regression analysis to predict health trends.  
- Apply clustering to group similar patterns in physical health metrics.  

---

## Project Plan

### **1. Preprocessing Data**
- Import and clean raw data.  
- Identify and separate relevant metrics.  

### **2. Exploratory Data Analysis**
- Visualize trends and correlations.  
- Highlight significant patterns in the data.  

### **3. Comparative Analysis**
- Compare changes in physical health metrics across academic terms, breaks, and internship periods.  

### **4. Results and Inferences**
- Summarize findings and propose actionable insights.  
- Highlight potential limitations and areas for improvement.  

### **5. Presentation**
- Compile results and methodologies into a detailed report.  
- Present key findings and recommendations.

 **[AppleHealth Notebook](https://github.com/cagatayeroglu/AppleHealth/blob/main/AppleHealth.ipynb)**  
  

---

## Expected Outcomes

1. A detailed analysis of how academic intensity influences physical health metrics.  
2. Insights into activity levels and energy expenditure trends across different academic and non-academic periods.  
3. Practical suggestions for balancing academic workload and maintaining physical well-being.  
4. Identification of outliers and their impact on physical health metrics.  

---

## Future Work

1. **Expand Dataset**  
   - Include additional metrics like sleep patterns, stress levels, and mood for a holistic analysis.  

2. **Collaborative Analysis**  
   - Compare findings with similar data from peers to identify common trends and outliers.  

3. **Automation**  
   - Develop automated tools for real-time health tracking and analysis.  

4. **Broader Scope**  
   - Extend the project to analyze the impact of other external factors, such as exam periods or seasonal changes.  

 **[FutureGuess Notebook](https://github.com/cagatayeroglu/AppleHealth/blob/main/FutureGuess.ipynb)**  


---





## Sabanci University Picture

[Sabanci University Logo](https://github.com/cagatayeroglu/AppleHealth/blob/main/1294_1_sabanciuniv.gif)
