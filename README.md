Aviation crews are classified as occupational radiation workers due to chronic exposure to galactic
cosmic rays (GCR) and solar energetic particles at cruising altitudes. Existing physics-based models
(NAIRAS, EPCARD) exhibit systematic discrepancies during geomagnetically active periods. This
study frames aviation radiation as a three-class classification problem—background (K = 0), moderate
(K = 1), and elevated (K = 2)—using a custom H-index scheme applied to the ARMAS ML-ready dataset
(92 476 measurements, 589 flights, 2013–2023). Six classifiers are benchmarked under a rotating three-fold
holdout strategy with SMOTE oversampling: Logistic Regression, Support Vector Machine, Decision Tree,
Random Forest, AdaBoost, and MLP. The mathematical formulation of each model is presented alongside
empirical results. AdaBoost achieves the best macro F1 score of 0.658 ± 0.004; Random Forest records
the highest ROC-AUC of 0.839 ± 0.006. All models exhibit a consistent ROC-AUC vs. F1-Macro gap of
approximately 0.18, attributable to imprecise boundary resolution at the moderate-elevated transition.
SHAP and permutation importance confirm altitude, geomagnetic latitude, and neutron monitor counts
as dominant predictors, consistent with physical theory.
