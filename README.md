# Machine learning approaches to predict anticancer drug sensitivity using transcriptomics data from cell lines

**Project Overview**

This project investigates the potential of machine-learning approaches to predict anticancer drug sensitivity using gene-expression profiles from cancer cell lines.

The study explores different modelling strategies, feature-selection approaches and biologically informed pathway-level representations to investigate predictive performance and model interpretability.

**Research Objectives**

1. Investigate associations between gene-expression profiles and anticancer drug response.

2. Compare different regression algorithms for drug-sensitivity prediction.

3. Evaluate manual and automated hyperparameter optimisation strategies.

4. Investigate dimensionality reduction and pathway-level feature representations.

5. Assess model generalisation using cross-validation and independent test data.

**Data Sources**

DepMap: Gene-expression profiles.

GDSC: Anticancer drug-response measurements.

Additional datasets and validation sources, where applicable.

Raw datasets are not included in this repository. Please refer to the original data providers for access and usage conditions.

**Methodology**

1. Exploratory data analysis and data preprocessing.

2. Gene-expression and drug-response data integration.

3. Baseline machine-learning models.

4. Manual and automated hyperparameter optimisation.

5. Gene-level feature selection.

6. Pathway-level feature engineering and activity scoring.

7. Model evaluation and comparison.

**Machine Learning Methods**

Random Forest Regression

XGBoost Regression

Support Vector Regression

Regularised regression models

**Repository Structure**

notebooks/: Exploratory analysis, feature engineering and modelling.

results/: Model evaluation tables and visualisations.

README.md: Project overview and documentation.

**Evaluation**

Models are assessed using appropriate regression metrics, including R², RMSE and correlation coefficients, alongside cross-validation and held-out evaluation.

**Limitations**

The analysis is subject to limitations associated with sample size, high-dimensional genomic features, biological heterogeneity and the translation of cell-line-based predictions to patient tumours.

**Future Directions**

1. Biological interpretation of predictive features.

2. Evaluation of pathway-level representations.

3. Independent validation using suitable patient-derived or external datasets.

4. Investigation of multi-omics approaches to drug-response prediction.

**Tools and Technologies**

Python, Pandas, NumPy, Scikit-learn, XGBoost, Optuna, Decoupler and Jupyter Notebook.
