## Exploratory Data Analysis (EDA)
### Digital Assignment

---

### Objective: The aim of this assignment is to analyze a dataset using Python, following a systematic approach through data exploration, preprocessing, statistical analysis, and model development.
---

### 1. **Account Setup**
   - **GitHub and Google Colab Linkage**: Created a GitHub account and connected it to Google Colab for streamlined workflow and version control.

---

### **Dataset Overview**
   - **Dimensions**: Analysis of the shape (rows, columns) of the dataset.
   - **Summary Statistics**: Basic descriptive statistics for numerical columns to understand distributions, ranges, and outliers.
   - **Data Attributes**: Initial research on dataset attributes to understand the significance of each variable.

---

### **Data Preprocessing**

#### A. **Handling Missing Values**
   - **Techniques Used**: Employed Maximum Likelihood Estimation (MLE) for missing values in numerical columns.
   - **Imputation**: Applied mean imputation as a basic technique to fill in gaps where MLE was not applicable.

#### B. **Data Cleaning**
   - **Outlier Detection and Removal**: Utilized Z-score with a threshold of ±3 to filter out extreme values in columns like `income` and `expenditure`.
   - **Value Replacement and Deduplication**: Replaced incorrect or duplicate values to ensure data accuracy.

#### C. **Data Transformation**
   - **Discretization and Binning**: Applied to continuous variables to facilitate further analysis.
   - **Encoding**: Encoded categorical variables as necessary.

---

### **Statistical Analysis**

#### A. **Univariate Analysis**
   - **Visualization Techniques**: Histograms and boxplots for individual variable distributions.
   - **Key Findings**: Insights into distributions, skewness, and variability.

#### B. **Bivariate Analysis**
   - **Correlation Heatmap**: Highlighted relationships between numerical variables.
   - **Scatter Plots**: Examined pairwise relationships, focusing on correlations like `income` vs. `expenditure`.

#### C. **Multivariate Analysis**
   - **PCA for Dimensionality Reduction**: Reduced dimensions to simplify the dataset while retaining maximum variance.
   - **Cluster Analysis**: Conducted model-based clustering and implemented the Expectation-Maximization algorithm to explore natural groupings in the data.

---


### **Model Development and Evaluation**

#### **Linear Regression Model**
   - **Model Building**: Constructed a linear regression model to predict reading scores based on other factors.
   - **Evaluation Metrics**: Computed R-squared and adjusted R-squared values to assess model fit.

### Appendix
   - **Code Repository**: [https://github.com/sakshipradeep03/EDA-Assignment]

--- 
