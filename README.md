Exploratory Data Analysis on Survey Data

---

### **Project Overview**
This project involves performing **Exploratory Data Analysis (EDA)** on a cleaned survey dataset to uncover insights into job preferences, programming language trends, and other key metrics. The analysis includes handling missing data, visualizing trends, and identifying correlations between key variables.

---

### **Objectives**
- Analyze remote work preferences by job role and employment type.
- Investigate programming language trends by region.
- Examine the relationship between experience and job satisfaction.
- Understand the correlation between educational background and employment type.
- Save the cleaned and analyzed dataset for further use.

---

### **Steps Performed**
1. **Data Preparation**:
   - Loaded the dataset from a provided URL.
   - Handled missing values in critical columns (`Employment`, `JobSat`, `RemoteWork`).

2. **Remote Work Preferences Analysis**:
   - Used a count plot to show the distribution of remote work preferences.
   - Cross-tabulated remote work preferences with employment types.

3. **Programming Language Trends**:
   - Filtered data by region to analyze popular programming languages.
   - Visualized the most-used programming languages using a bar plot.

4. **Experience vs. Job Satisfaction**:
   - Created experience ranges from the `YearsCodePro` column.
   - Visualized the correlation between years of experience and job satisfaction using scatter plots.

5. **Educational Background vs. Employment Type**:
   - Cross-tabulated education level with employment types.
   - Visualized the relationship using heatmaps.

6. **Saving the Dataset**:
   - Saved the cleaned and analyzed dataset as a CSV file for future use.

---

### **Tools and Libraries Used**
- **Libraries**: pandas, matplotlib, seaborn, numpy
- **Techniques**:
  - Handling missing data
  - Data visualization (count plots, bar plots, scatter plots, heatmaps)
  - Correlation analysis and aggregation

---

### **Insights Derived**
- Identified trends in remote work preferences by job roles and employment types.
- Discovered popular programming languages in different regions.
- Highlighted the correlation between professional experience and job satisfaction.
- Explored the impact of educational background on employment types.

---

### **Output**
The cleaned and analyzed dataset has been saved as:
`cleaned_analyzed_dataset.csv`

---


