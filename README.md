# Statistical Analysis

This repository contains two distinct statistical analysis projects. One investigates **dropout rates in schools**, and the other explores the **determinants of women’s principal resource provider status** in households. Both projects apply a range of statistical techniques to analyze and visualize data, providing valuable insights into educational and social dynamics.

## **1. Statistical Analysis of Dropout Rates in Schools**

### **Project Overview**
This analysis examines dropout rates in schools, focusing on various factors such as gender, school sector (public vs private), and region. Several statistical tests are conducted to identify significant relationships within the data, complemented by visualizations to support the findings.

### **Objective**
To identify the main factors contributing to variations in dropout rates across different regions, sectors, and genders.

### **Key Steps in the Analysis**
1. **Kruskal-Wallis Test**:  
   - Compares dropout rates across multiple regions.  
   - A non-parametric test to evaluate differences among more than two independent groups.

2. **Dunn’s Post-Hoc Test**:  
   - Applied if Kruskal-Wallis reveals significant differences to pinpoint specific group differences.

3. **Mann-Whitney U Test**:  
   - Compares dropout rates between public and private schools, for both boys and girls.

4. **Median Comparison**:  
   - Compares the medians of dropout rates across different groups (e.g., public vs private, boys vs girls).

5. **Correlation Analysis**:  
   - Pearson and Spearman correlations are used to explore relationships between school size and dropout rates.

6. **Visualizations**:  
   - Various plots (e.g., boxplots, scatter plots) visualize the distribution of dropout rates by gender, sector, and region.

### **Libraries Used**
- `pandas`, `matplotlib`, `seaborn`, `scipy`, `statsmodels`

### **Steps for Running the Analysis**
1. **Data Preparation**: Clean and format the dataset, handling missing values.
2. **Statistical Tests**: Apply Kruskal-Wallis, Mann-Whitney U, and Dunn’s tests, and compare medians.
3. **Visualizations**: Generate boxplots and scatter plots.
4. **Results Interpretation**: Interpret p-values and test outcomes to draw conclusions.

### **Code Structure**
- **Statistical Tests Section**: Implements Kruskal-Wallis, Mann-Whitney U, and Dunn’s tests.
- **Data Visualization Section**: Generates graphical representations of data.
- **Data Preparation Section**: Includes data pre-processing steps.

### **Important Notes**
- Non-parametric tests are used due to unknown distribution in the data.
- A significance level of 0.05 is applied to all statistical tests.

### **Conclusion**
This analysis identifies key factors influencing dropout rates across regions, school sectors, and genders, providing valuable insights for policy decisions and targeted interventions.

---

## **2. Determinants of Women’s Principal Resource Provider Status**

### **Project Overview**
This analysis explores factors influencing whether a woman is the primary breadwinner in her household, using binary logistic regression. The dataset includes individuals living in couples, with various potential influencing factors.

### **Objective**
To identify and assess the key factors that predict whether a woman is the principal earner in a household.

### **Libraries Used**
- `pandas`, `numpy`, `matplotlib`, `seaborn`, `statsmodels`, `scipy`, `sklearn`

### **Steps Taken**
1. **Data Loading & Initial Exploration**:  
   - Load the dataset from `.sas7bdat` format and filter data to include individuals in couples.  
   - Define the target variable `FPA` (Female Principal Earner) based on household conditions.

2. **Data Cleaning**:  
   - Handle missing values by replacing them with zeros.  
   - Focus on relevant variables for analysis.

3. **Exploratory Data Analysis (EDA)**:  
   - Generate plots (histograms, Q-Q plots) for continuous variables.  
   - Create correlation matrices and contingency tables for categorical variables.

4. **Statistical Testing**:  
   - Perform a t-test to analyze significant differences in means based on the target variable (`FPA`).

5. **Feature Selection**:  
   - Identify significant predictors (e.g., `NPERS`, `NACTIFS`, `REVMENUC`) for further modeling.

6. **Logistic Regression Model**:  
   - Train a logistic regression model using the selected features.  
   - Evaluate model performance using precision, recall, and ROC-AUC metrics.

### **Key Insights**
- Significant predictors include the number of people in the household (`NPERS`), the number of active workers (`NACTIFS`), and household income (`REVMENUC`).
- Correlation analysis reveals relationships between household size, income, and the likelihood of a woman being the primary earner.

### **Remaining Work**
- Refine the logistic regression model by exploring additional features and handling multicollinearity.
- Implement cross-validation and explore feature interactions for deeper insights.

---

## **General Notes**
- **Data Formats**: Each project uses different dataset formats. The first project uses CSV, while the second uses a `.sas7bdat` file.
- **Assumptions**: Non-parametric tests are used for non-normally distributed data.
- **Significance Level**: A significance threshold of 0.05 is applied to all statistical tests in both projects.
