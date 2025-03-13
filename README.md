**Car Sales Data Analysis Report**

--- 
**Student Name:** Pranav Reddy Pedaballe  
---

## **1. Introduction**

This report presents a comprehensive analysis of a car sales dataset consisting of 23,906 entries and 16 attributes. The primary objective of this study is to apply data cleaning techniques, conduct exploratory data analysis (EDA), and examine relationships between variables to extract meaningful insights. The dataset includes numerical and categorical variables, and it may contain missing values, duplicates, and outliers that need to be addressed.

## **2. Data Cleaning**

Data cleaning is a crucial step in ensuring the accuracy and reliability of the dataset. The following steps were performed:

### **2.1 Handling Missing Values**
- A thorough inspection of the dataset revealed no missing values across all columns.

### **2.2 Identifying and Removing Duplicates**
- No duplicate records were found in the dataset.

### **2.3 Outlier Detection and Treatment**
- The z-score method was employed to identify outliers in numerical columns.
- Outliers were detected in the following attributes:
  - **Annual Income:** 336 outliers identified.
  - **Price ($):** 351 outliers identified.
- Outliers were removed, reducing the dataset size to 23226 records from 23906.

### **2.4 Converting the date from onject type to Datetime type**

## **3. Exploratory Data Analysis (EDA)**

EDA was conducted to explore the dataset's characteristics and relationships between variables. The analysis was performed at three levels: univariate, bivariate, and multivariate.

### **3.1 Univariate Analysis**

#### **Descriptive Statistics:**
- **Annual Income:**
  - Mean: $830,840
  - Standard Deviation: $720,006
  - Distribution: Right-skewed
- **Price ($):**
  - Mean: $28,090
  - Standard Deviation: $14,788

#### **Visual Representations:**
- **Numerical variables**
  - **Histograms and Density Plots and Box Plots:**
    - Both "Annual Income" and "Price ($)" exhibited a right-skewed distribution.
-**Categorical variables**
  -**Bar graphs and Pie Charts**

### **3.2 Bivariate Analysis**

#### **Correlation Analysis:**
- A correlation matrix revealed a weak positive correlation (r ≈ 0.3) between "Annual Income" and "Price ($)," indicating that higher-income customers tend to purchase more expensive cars, albeit with significant variability.

#### **Scatter Plot Analysis:**
- A scatter plot of "Annual Income" vs. "Price ($)" highlighted a dispersed trend, reinforcing the weak correlation between these variables.

#### **Box Plot Analysis:**
- A box plot comparing "Gender" and "Price ($)" indicated no significant differences in car prices between male and female customers.

### **3.3 Multivariate Analysis**

#### **Heatmap Analysis:**
- A heatmap of numerical variables confirmed weak correlations between "Annual Income" and "Price ($)."

#### **Categorical Analysis:**
- Grouped box plots and other visualizations did not reveal strong relationships between categorical variables (e.g., "Body Style," "Company") and price.

## **4. Conclusion**

This analysis provides key insights into customer demographics and purchasing behavior in the car sales dataset. The following conclusions can be drawn:

1. **Income Influence on Price:** While customers with higher incomes tend to purchase higher-priced vehicles, the relationship is not strongly linear.
2. **Gender and Car Price:** There is no significant difference in the average price of cars purchased by male and female customers.
3. **Data Integrity:** The dataset is free of missing values and duplicate records, with necessary outlier treatments performed.
4. **Future Considerations:** Additional external factors (e.g., geographic location, customer preferences, economic conditions) should be considered for a deeper analysis.

---

**References:**
[Include any references used for analysis, such as datasets, academic papers, or statistical methods.]

**Appendices:**
[Include any additional charts, tables, or data visualizations as needed.]

---

**End of Report**

