# projet-statistique

---

# **Statistical Analysis of Dropout Rates in Schools**

This project performs various statistical analyses and visualizations on dropout rates in schools based on the dataset provided. It includes tests like Kruskal-Wallis, Dunn’s test, Mann-Whitney U test, and comparisons of medians, along with relevant visualizations of the data by different factors like gender, sector (public vs private), and region.

## **Project Overview**

The goal of this analysis is to explore dropout rates across different variables, including gender, school sector (public vs private), and region. Various statistical methods are employed to test hypotheses, including tests for significant differences in dropout rates, correlations, and visual representation of the data.

### **Key Steps in the Analysis:**

1. **Kruskal-Wallis Test**
   - Used to compare the dropout rates across multiple regions.
   - A non-parametric test for comparing more than two independent groups.

2. **Dunn's Post-Hoc Test**
   - If the Kruskal-Wallis test reveals significant differences, Dunn's test is applied to identify which specific groups differ.

3. **Mann-Whitney U Test**
   - Used to compare dropout rates between public and private schools for both boys and girls.
   - Non-parametric test used when comparing two independent groups.

4. **Median Comparison**
   - Median dropout rates are calculated and compared for different groups (public vs private schools, boys vs girls).
   - Differences in medians are explored to understand if there are notable variations.

5. **Correlation Analysis**
   - Pearson and Spearman correlations are computed to explore relationships between school size (total number of students) and dropout rates for both boys and girls.

6. **Visualizations**
   - Various plots, including boxplots and scatter plots, are created to visualize the distribution of dropout rates by gender, sector, and region.

## **Libraries Used:**

- `pandas` for data manipulation
- `matplotlib` and `seaborn` for visualizations
- `scipy` for statistical tests
- `statsmodels` for additional statistical methods (e.g., Kruskal-Wallis and Dunn tests)

## **Steps for Running the Analysis:**

1. **Data Preparation:**
   - Ensure that the dataset is cleaned and formatted properly (e.g., handling missing values).

2. **Statistical Tests:**
   - Apply the Kruskal-Wallis test for regional comparisons of dropout rates.
   - Perform Dunn’s test if Kruskal-Wallis results are significant.
   - Use the Mann-Whitney U test to compare dropout rates between public and private schools.
   - Compare medians to investigate differences in dropout rates between different groups.

3. **Visualizations:**
   - Generate boxplots to show the distribution of dropout rates by region and gender.
   - Create scatter plots to explore correlations between school size and dropout rates.

4. **Results Interpretation:**
   - Interpret the results from the statistical tests and visualize the data accordingly.
   - Based on p-values, draw conclusions about whether significant differences exist in dropout rates between groups.

## **Code Structure:**

- **Statistical Tests Section:**
  - Kruskal-Wallis, Mann-Whitney U, and Dunn’s tests are implemented here to compare dropout rates across different groups.

- **Data Visualization Section:**
  - Plots (scatter, boxplots) are generated to represent the data graphically.

- **Data Preparation Section:**
  - Data is pre-processed (e.g., melting the dataframe for easier plotting).

## **Important Notes:**

- **Assumptions:** 
  - The non-parametric tests assume that the data does not follow a normal distribution. These tests are suitable for data with unknown distribution or ordinal data.
  
- **Significance Level:**
  - A p-value threshold of 0.05 is used for statistical significance.

## **Conclusion:**
This analysis helps identify significant differences in dropout rates across different regions, sectors, and genders. It provides insights into where interventions might be needed and whether the gender or type of school (public vs private) plays a significant role in dropout rates.

---

