THE IMPACT OF ACADEMIC INTENSITY AND CAMPUS MOBILITY ON PHYSICAL ACTIVITY: AN ANALYSIS OF APPLE HEALTH STEP COUNT DATA AT SABANCI UNIVERSITY

Introduction
Sabancı University has a large campus with classrooms located far apart, which affects students' daily physical activity. During academic terms, campus mobility increases step counts, while during summer and midterm breaks and even during weekends in terms, step counts may decrease. However, individual cases like internships or jobs during holidays can lead to higher step counts and deviate from general trends. This project aims to study how academic periods and campus life affect students' physical activity, analyze seasonal differences, and explain these unique cases (outliers).

Objective

The project aims to analyze how academic schedules and campus size impact step counts. Specifically:

To compare step counts during academic terms, summer holidays, and midterm breaks.

To examine the difference between weekday and weekend step counts.

To understand how unique cases (like internships) affect general trends.

Hypotheses

H1: Step counts increase as program intensity increases.

H2: Step counts during summer and midterm breaks are lower than during academic terms.

H3: Weekday step counts are higher due to campus mobility, while weekend step counts decrease.

H4: Internships may lead to higher step counts during holiday periods.

H5: Weekend step counts decrease due to reduced academic activity.

Methodology

1. Data Collection

Source: Step count data from Apple Health (in XML format).

Time Frame: October 3, 2022 – September 23, 2024.

Groups:

2022-2023 Academic Term: October 3 - January 20 / February 27 - June 11

2023-2024 Academic Term: October 2 - January 19 / February 15 - June 9

Summer Break: June 11 - October 2 (2023) / June 11 - September 23 (2024)

Midterm Break: January 15 - February 15

Internship Periods: January 29 - February 9, 2024; July 4 - 28, 2024; September 2 - 20, 2024

Weekdays vs Weekends: Data will also be classified by weekday and weekend.

2. Data Processing

Tools & Environment:

Data will be processed using Python in a Jupyter Notebook.

Libraries: pandas, xml.etree.ElementTree, matplotlib, seaborn, numpy.

Steps for Processing XML Data:

Reading XML Files:

Use xml.etree.ElementTree to parse the Apple Health XML data file.

Extract relevant fields: date, step count etc. (e.g., device type).

Convert the data into a structured format like a DataFrame for analysis.

Filtering Relevant Data:

Focus only on step count data (HKQuantityTypeIdentifierStepCount).

Filter data by date ranges corresponding to academic terms, holidays, and internships.

Categorizing Data:

Group daily step counts into specific categories:

Academic Term, Midterm Break, Summer Holiday, Internship.

Split data into Weekday and Weekend categories.


Outlier Handling:

Identify outliers (e.g., internship days with unusually high step counts).

Highlight these outliers for further analysis in graphs.

3. Data Analysis

Step Count Categorization:

Daily step counts will be grouped based on the periods above.

Outlier Analysis:

Special analysis will focus on internship periods to identify deviations from holiday trends.

Weekday vs Weekend Comparison:

Step counts during academic terms will be compared to measure the impact of Sabancı's academic program intensity.

Statistical Methods:

Group comparisons (e.g., summer vs academic terms, weekends vs weekdays).

Time series analysis to track step count changes over time.

T-tests to compare weekday and weekend step counts during terms.

4. Visualization

Bar Charts:
Show average step counts for each category (academic term, holiday, midterm break).

Line Graphs:
Display daily step count trends throughout the year.

Highlight Outliers:
Use markers or colors to emphasize internship periods or deviations.
Clean Pure Data:

Extract only weekday data during academic terms for focused analyses.

Expected Results

Academic Terms:

Step counts will be higher due to campus mobility.

Summer and Midterm Breaks:

Step counts will decrease compared to academic terms.

Internship Periods:

Step counts may increase during internships, differing from holiday trends.

Weekdays vs Weekends:

Step counts will be higher on weekdays than weekends during academic terms.

Project Contributions

Provide insights into how academic schedules and campus mobility influence physical activity.
Help students and university management understand the impact of campus layout on daily activity.
Highlight unique cases (e.g., internships) to show outliers.
