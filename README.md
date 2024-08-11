# DS110 Final Project: Predicting Bechdel Test Outcomes

## Project Overview

This project aims to analyze gender representation in films using the Bechdel Test as a measure of gender inclusivity. We explore whether the likelihood of a film passing the Bechdel Test can be predicted based on its release year, specifically examining the impact of the second wave of the Women's Rights Movement around 1960.

## Team Members

- Ava Yip
- Menahil Bakhat
- Sitong Lu

## Dataset

We utilized the [Female Representation in Cinema dataset](https://www.kaggle.com/datasets/vinifm/female-representation-in-cinema) from Kaggle, focusing on Bechdel Test Scores.

## Central Question

Can we predict whether a film passes the Bechdel Test based on whether it was released before or after 1960, marking the second wave of the Women’s Rights Movement?

## Methodology

### Data Preparation

- **Cleaning:** Removed films with dubious or unclear scores.
- **Transformation:** Converted Bechdel test scores to boolean variables (pass/fail) and release years to boolean variables (before/after 1960).

### Statistical Analysis

1. **Chi-Square Test:** Assessed the relationship between Bechdel Test outcomes and release years.
2. **Correlation Analysis:** Analyzed the correlation between Bechdel Test scores and release years.

### Machine Learning Models

1. **Decision Tree:**
   - **Input Features:** Binary variables for release year and Bechdel test score.
   - **Prediction:** Whether a film passes the Bechdel Test.
   - **Optimization:** Tested different maximum depths for improved accuracy.

2. **Random Forest:**
   - **Input Features:** Same as the Decision Tree.
   - **Prediction:** Whether a film passes the Bechdel Test.
   - **Optimization:** Adjusted the number of estimators for better performance.

### Visualizations

1. **Bar Chart:** Comparison of films passing the Bechdel Test before and after 1960.
2. **Scatter Plot (Seaborn):** Relationship between Bechdel Test results and release year.
3. **Linear Regression:** Relationship between Bechdel Test pass/fail status and film attributes (genre, budget, etc.).

## Results

- **Statistical Significance:** A significant relationship between release date and Bechdel Test outcomes (p-value < 0.05).
- **Machine Learning Accuracy:** Decision Tree achieved 60.44% accuracy in predicting the time period based on film attributes.
- **Correlation Findings:** Weak positive correlation between release year and female representation in cast.

## Conclusion

Our analysis highlights the influence of historical social movements on gender representation in films. Although there is a positive trend towards gender inclusivity in newer films, disparities in male and female representation persist in the film industry.

## Future Work

Further research could explore additional factors affecting gender representation and develop more complex models to predict Bechdel Test outcomes.

## Acknowledgments

We thank our instructors and peers for their support and guidance throughout this project.
