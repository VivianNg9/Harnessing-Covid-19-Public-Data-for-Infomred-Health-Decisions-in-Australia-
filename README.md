# __<center>Harnessing Covid-19 Public Data for Informed Health Decision in Australia</center>__
[This project](https://github.com/VivianNg9/Harnessing-Covid-19-Public-Data-for-Infomred-Health-Decisions-in-Australia-/blob/main/Harnessing%20Covid-19%20Public%20Health%20Data%20for%20Informed%20Health%20Decisions%20in%20Australia.pdf) applies data-driven methods to analyze and understand the COVID-19 pandemic in Australia. By combining descriptive analysis, K-Means clustering, and hypothesis testing, the project generates actionable insights to support public health policies and pandemic response strategies.

## Objectives

1. Explore global and national trends to understand pandemic dynamics.
2. Analyze demographic, socioeconomic, and policy-related factors influencing COVID-19 outcomes.
3. Identify key predictors of mortality, vaccination impacts, and healthcare outcomes using statistical and machine learning techniques.

## Analytical Methods

### 1. Descriptive Analysis
- Conducted a detailed exploration of pandemic trends:
  - Case counts, death rates, and vaccination trajectories in Australia and globally.
  - Temporal analysis of the pandemic waves and their characteristics.
- Highlighted shifts in mortality and infection rates due to interventions (e.g., lockdowns, vaccinations).

### 2. K-Means Clustering
- Grouped countries based on pandemic-related indicators (e.g., GDP per capita, vaccination rates, healthcare capacity):
  - Discovered clusters representing distinct pandemic experiences (e.g., high-income nations vs. low-resource countries).
- Unveiled patterns linking economic/demographic factors to pandemic outcomes.

### 3. Hypothesis Testing
- Performed statistical hypothesis testing to validate relationships between variables:
  - Correlations between policy stringency and infection/mortality rates.
  - Lagged effects in case reporting between countries.
- Used hypothesis testing to assess vaccine efficacy and the role of comorbidities in mortality.

## Key Insights

1. **Global and National Trends**:
   - Four distinct COVID-19 waves in Australia, with a significant decoupling of case and death rates post-vaccination.
   - Rapid vaccination rollout helped mitigate the Omicron wave's impacts.

2. **Clustering Analysis**:
   - Countries in the same cluster exhibited shared pandemic characteristics, highlighting the role of socioeconomic factors in shaping responses.

3. **Vaccination and Mortality**:
   - Vaccination rates significantly correlated with reduced ICU admissions and deaths, especially among high-risk age groups.

4. **Policy Effectiveness**:
   - Moderate relationship between policy stringency and R-values, suggesting that other factors influenced the outcomes.

## Tools and Technologies
- **Programming Languages**: Python (Pandas, NumPy, Matplotlib, Scikit-learn, SciPy).
- **Data Sources**: Our World in Data (OWID), Australian Bureau of Statistics, WHO.
- **Statistical Methods**: Correlation analysis, hypothesis testing, and regression models.
- **Machine Learning Models**: K-Means clustering, SHAP for interpretability, XGBoost for mortality predictions.

## Visualizations
To illustrate these insights, the repository includes:
- Line charts depicting pandemic waves and vaccination rollouts.
- Clustering visualizations showing country groupings.
- Regression and SHAP plots for predictors of mortality.

## Conclusion
This project demonstrates the power of analytical tools in shaping pandemic responses and public health policies. By leveraging descriptive, clustering, and statistical methods, it provides a holistic view of the pandemic's impacts and actionable insights for informed decision-making.
