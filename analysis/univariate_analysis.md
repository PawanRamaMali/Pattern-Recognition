# Univariate Analysis Steps

Univariate analysis involves examining and describing a single variable's distribution and characteristics in a dataset. Here’s a detailed step-by-step approach to performing univariate analysis:

## 1. Define the Variable Type
   - **Categorical Variables:** These include nominal (e.g., gender, race) and ordinal variables (e.g., rating scales, income brackets).
   - **Continuous Variables:** These are numeric variables that can take an infinite number of values (e.g., height, weight, temperature).

## 2. Data Summarization
   - **Categorical Data:** 
      - Use frequency tables to count occurrences of each category.
      - Calculate relative frequencies (proportions or percentages) to understand the distribution.
   - **Continuous Data:** 
      - Calculate summary statistics such as:
        - **Mean:** The average value.
        - **Median:** The middle value when data is sorted.
        - **Mode:** The most frequently occurring value.
        - **Range:** Difference between the maximum and minimum values.
        - **Variance and Standard Deviation:** Measures of spread or dispersion.
        - **Quantiles (e.g., quartiles, percentiles):** To understand the distribution shape.

## 3. Visual Representation
   - **Categorical Data:**
      - **Bar Charts:** Useful for displaying frequency counts of categories.
      - **Pie Charts:** Show proportions, but are less favored in statistical analysis due to poor visual comparison.
   - **Continuous Data:**
      - **Histograms:** Show the frequency distribution across ranges (bins).
      - **Box Plots:** Display the median, quartiles, and potential outliers.
      - **Density Plots:** Represent the data's probability density function, providing a smooth curve to depict distribution.

## 4. Assess Distribution Characteristics (Continuous Data)
   - **Shape of Distribution:**
      - **Normal Distribution:** Symmetrical, bell-shaped.
      - **Skewness:** Indicates asymmetry. Positive skew means a longer right tail, while negative skew implies a longer left tail.
      - **Kurtosis:** Measures the "tailedness" of the distribution. High kurtosis means more outliers, while low kurtosis indicates fewer.
   - **Outlier Detection:**
      - Use box plots or statistical rules (e.g., values lying more than 1.5 times the interquartile range away from the quartiles) to identify outliers.
   - **Normality Test:**
      - **Q-Q Plot (Quantile-Quantile Plot):** Compares data quantiles against a theoretical normal distribution.
      - **Shapiro-Wilk or Kolmogorov-Smirnov Tests:** Statistical tests to assess if the data follows a normal distribution.

## 5. Hypothesis Testing (If Applicable)
   - For continuous data, consider whether the sample mean differs significantly from a known population mean using t-tests.
   - For categorical data, perform chi-square tests to determine if distributions differ from expectations.

## 6. Transformations (If Necessary)
   - If the data is not normally distributed, transformations (e.g., log, square root, Box-Cox) may help in normalizing the distribution.

## 7. Interpretation
   - Based on the summaries and visualizations, draw conclusions about the variable’s central tendency, variability, and overall distribution.
   - Discuss any patterns, anomalies, or specific characteristics that may impact further analyses.

By following these steps, univariate analysis can provide insights into a dataset's individual variables, laying the groundwork for more complex multivariate analyses.
