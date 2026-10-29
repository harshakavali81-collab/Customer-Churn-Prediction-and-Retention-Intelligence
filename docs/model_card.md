# Model card — Customer Churn Prediction and Retention Intelligence

Task: churn; source: Synthetic subscription and support history.

## Evaluation
- Logistic Regression: PR-AUC = 0.3663
- Random Forest: PR-AUC = 0.2370

Split: stratified holdout. The supplied results are deterministic educational demonstrations, not real-world benchmarks or deployment approvals.

## Risks
Training data is synthetic. Statistical estimates may not transfer to real events. Audit fairness, calibration, input distributions, access controls and domain-specific safety before external use.
