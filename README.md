# __<center>Harnessing Covid-19 Public Data for Informed Health Decision in Australia</center>__
[This project](https://github.com/VivianNg9/Harnessing-Covid-19-Public-Data-for-Infomred-Health-Decisions-in-Australia-/blob/main/Harnessing%20Covid-19%20Public%20Health%20Data%20for%20Informed%20Health%20Decisions%20in%20Australia.pdf) delivers key insights on the COVID-19 pandemic to support the Agency for Clinical Innovation (ACI) at NSW Health in crafting data-informed public health strategies. By analyzing extensive publicly available COVID-19 data, both nationally and internationally, the project applies descriptive analysis, K-Means clustering, hypothesis testing to map the pandemic’s trajectory and assess the effectiveness of interventions.

## Tools 
- **Programming Languages**: Python (Pandas, NumPy, Matplotlib, Scikit-learn, SciPy).
- **Data Sources**: [Our World in Data (OWID)](https://github.com/owid/covid-19-data/tree/master/public/data)
- **Statistical Methods**: Correlation analysis, hypothesis testing, and regression models.
- **Machine Learning Models**: K-Means clustering, SHAP for interpretability, XGBoost for mortality predictions.
  
## Objectives

1. Explore global and national trends to understand pandemic dynamics.
2. Analyse demographic, socioeconomic, and policy-related factors influencing COVID-19 outcomes.
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

![Pandemic Period](https://github.com/VivianNg9/Harnessing-Covid-19-Public-Data-for-Infomred-Health-Decisions-in-Australia-/blob/main/image%20/pandemic%20period.png)
  
Australia experienced four major COVID-19 waves, with early border closures and a robust vaccination drive keeping initial infection rates low. The Delta variant prompted policy shifts, while the Omicron surge in 2021 tested healthcare systems despite high vaccination coverage, leading to increased fatalities and evolving pandemic management strategies.


2. **Clustering Analysis**:
   - Countries in the same cluster exhibited shared pandemic characteristics, highlighting the role of socioeconomic factors in shaping responses.
   - 
![clustering](https://github.com/VivianNg9/Harnessing-Covid-19-Public-Data-for-Infomred-Health-Decisions-in-Australia-/blob/main/image%20/clustering.png)

A world map visualization of clustering analysis highlighted geographic distributions, with high-income countries (Cluster 0) concentrated in Europe, North America, and parts of Asia and Oceania, while Cluster 1 included countries across Africa, Asia, and Latin America. Cluster 2 was limited to China and India, emphasizing their unique demographic and population dynamics. The analysis demonstrated how economic capabilities and demographics shaped countries’ pandemic experiences and responses. These findings underscore the importance of tailoring pandemic strategies to specific cluster needs and fostering collaboration and resource sharing among similar nations. Future research should investigate evolving factors like vaccination uptake and policy adaptations for a comprehensive understanding of pandemic responses.
3. **Vaccination and Mortality**:
   - Vaccination rates significantly correlated with reduced ICU admissions and deaths, especially among high-risk age groups.

4. **Policy Effectiveness**:
   - Moderate relationship between policy stringency and R-values, suggesting that other factors influenced the outcomes.


## Conclusion
This project demonstrates the power of analytical tools in shaping pandemic responses and public health policies. By leveraging descriptive, clustering, and statistical methods, it provides a holistic view of the pandemic's impacts and actionable insights for informed decision-making.
