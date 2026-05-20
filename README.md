Project Title
- Education Level Impacts Income

Dataset
- The original dataset was obtained from UCI Machine Learning Repository
- The features and outcome in the datesets are:
  - age
  - workclass
  - education
  - race
  - sex
  - capital-gain
  - capital-loss
  - hours-per-week
  - native country
  - income

Objective
- Find out which features affect income using logistic regression.

Methods
- Uses logistic regression to identify coefficients of each feature. These coefficients interpreted as the magnitude of impact on a person's income. High positive coefficient means bigger positive impact, while high negative coefficient means bigger negative impact on income.
- The model was validated using ROC curve and AUC score. 

Key Findings
- Education plays a key role in determining a person's income, compared to other features.
- Professor, Doctorate, and Masters level of education recorded the biggest positive impact on income.
- While those with 7th-8th, 11th, and 9th grade level of education recorded the biggest negative impact on income.
- The model that used to determine these features' impact on income was validated using ROC curve and AUC score.
- The ROC curve shows how well the model can distinguish people who earn more than $50k than from those who earn less. The curve stays above baseline, meaning the model correctly identifies high earners and low earners at different decision points. This suggests the model is reliable for making predictions about income levels.
- The model has an AUC score of 0.8 (closer to 1 is better). This proves model has strong performance and good ability to distinguish between people with income less than or equal to $50k, against people with income more than $50k.
