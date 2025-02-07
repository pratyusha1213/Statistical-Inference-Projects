# Wine Quality Analysis

## Project Overview
This project focuses on analyzing the **Red Wine Quality dataset** using **Exploratory Data Analysis (EDA)** and statistical methods. The goal is to identify key factors influencing wine quality and alcohol levels, providing valuable insights for winemakers and consumers.

## Dataset
The dataset contains 12 attributes that describe the physicochemical properties of red wine samples. The key features include:
- **Fixed acidity**
- **Volatile acidity**
- **Citric acid**
- **Residual sugar**
- **Chlorides**
- **Free sulfur dioxide**
- **Total sulfur dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality (target variable)**

## Key Objectives
- Perform **data cleaning** and handle any missing or inconsistent values.
- Conduct **Exploratory Data Analysis (EDA)** to understand variable distributions and relationships.
- Analyze **correlation** between wine quality and different physicochemical properties.
- Identify **important factors** influencing wine quality using statistical methods.
- Perform **hypothesis testing** to validate findings.

## Methodology
1. **Data Preprocessing**
   - Checking for missing values
   - Handling outliers using IQR method
   - Standardizing numerical variables (if needed)

2. **Exploratory Data Analysis (EDA)**
   - Summary statistics (mean, median, standard deviation)
   - Histograms and box plots for distribution analysis
   - Scatter plots and heatmaps for correlation analysis

3. **Statistical Analysis**
   - Hypothesis testing (e.g., t-tests, ANOVA) to identify significant features
   - Confidence intervals for variable estimates
   - Multicollinearity analysis using Variance Inflation Factor (VIF)

## Insights & Findings
- None of the attributes in the dataset follow a normal (Gaussian) distribution.
- No regressors exhibit high or very high correlation with the target variables (alcohol, quality).
- Due to multicollinearity issues, Fixed Acidity was excluded from predictive models.
- Many attributes contain outliers, but these represent extreme values rather than data entry errors, so they were retained.
- Free Sulfur Dioxide was removed from the Linear Regression model due to its insignificance.
- Despite a slight violation of residual normality, all assumptions for linear regression were met, and the model achieved an R-squared of 59%.
- Feature scaling improved the performance of the Logistic Regression model, achieving an F1-score of 76% for classification.

## Tools & Technologies Used
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, SciPy)
- **Jupyter Notebook** for interactive analysis

## How to Run the Project
1. Install required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
2. Open the Jupyter Notebook and run the analysis step-by-step.
3. Explore the visualizations and statistical insights.

## Future Improvements
- Expand the analysis by incorporating **additional statistical tests** to strengthen findings.
- Integrate **time-series analysis** to study wine quality trends over time.
- Conduct a **comparative study** between red and white wines to uncover broader patterns.
- Utilize **advanced feature selection techniques** to refine variable selection and improve insights.
- Explore **geographical and climate data** to assess their impact on wine quality.


