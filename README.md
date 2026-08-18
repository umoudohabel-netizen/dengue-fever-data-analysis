# dengue-fever-data-analysis
Data analysis of dengue fever trends to identify patterns and support public-health decision-making.

# Predicting Dengue Severity and ICU Admission

## An Interpretable Machine Learning Approach Using Integrated Clinical, Behavioural and Environmental Data

## Project overview

Dengue fever remains a significant public-health challenge in Pakistan, particularly in Khyber Pakhtunkhwa, where seasonal outbreaks, environmental conditions and differences in clinical presentation can place pressure on healthcare resources.

This project develops interpretable machine-learning models to predict:

1. The likelihood that a patient may require intensive-care admission.
2. The clinical severity category of dengue infection.

The analysis combines patient-level clinical, laboratory, demographic and behavioural information with district-level environmental and entomological indicators. The project focuses on dengue cases recorded across four districts of Khyber Pakhtunkhwa, Pakistan, between 2019 and 2024.

The central aim is to investigate whether admission-time information can support earlier risk stratification and more informed clinical and public-health decision-making.

> **Important:** This project is for research and educational purposes only. It is not a clinical diagnostic tool and must not be used to make medical decisions.

## Research questions

- Can machine-learning models predict dengue-related ICU admission?
- Can machine-learning models classify dengue cases according to clinically informed severity categories?
- Which clinical, laboratory, behavioural and environmental variables contribute most to model predictions?
- Can SHAP explainability improve understanding of the factors associated with predicted dengue risk?
- Do admission-time laboratory markers provide stronger patient-level predictive information than broader environmental variables?

## Dataset

The analysis used two integrated datasets:

- A virology dataset containing **2,384 laboratory-confirmed dengue cases** and 52 variables.
- A climate and environmental dataset containing **3,015 records** and 18 variables before aggregation.

The data covered four districts in Khyber Pakhtunkhwa:

- Peshawar
- Nowshera
- Charsadda
- Mardan

The final integrated dataset contained **2,384 observations and 66 columns**. After removing target-derived and potential leakage variables, **56
