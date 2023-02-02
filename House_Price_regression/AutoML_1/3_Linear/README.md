# Summary of 3_Linear

[<< Go back](../README.md)


## Linear Regression (Linear)
- **n_jobs**: -1
- **explain_level**: 2

## Validation
 - **validation_type**: split
 - **train_ratio**: 0.75
 - **shuffle**: True

## Optimized metric
rmse

## Training time

2.0 seconds

### Metric details:
| Metric   |     Score |
|:---------|----------:|
| MAE      |  3.90652  |
| MSE      | 29.3195   |
| RMSE     |  5.41475  |
| R2       |  0.638982 |
| MAPE     |  0.210273 |



## Learning curves
![Learning curves](learning_curves.png)

## Coefficients
| feature   |    Learner_1 |
|:----------|-------------:|
| CHAS      |  0.384228    |
| RM        |  0.340198    |
| RAD       |  0.181854    |
| B         |  0.0876072   |
| ZN        |  0.0731394   |
| AGE       |  0.0354793   |
| INDUS     | -0.000105116 |
| intercept | -0.0304339   |
| CRIM      | -0.0344818   |
| TAX       | -0.127702    |
| PTRATIO   | -0.218451    |
| NOX       | -0.307692    |
| DIS       | -0.313611    |
| LSTAT     | -0.349021    |


## Permutation-based Importance
![Permutation-based Importance](permutation_importance.png)
## True vs Predicted

![True vs Predicted](true_vs_predicted.png)


## Predicted vs Residuals

![Predicted vs Residuals](predicted_vs_residuals.png)



## SHAP Importance
![SHAP Importance](shap_importance.png)

## SHAP Dependence plots

### Dependence (Fold 1)
![SHAP Dependence from Fold 1](learner_fold_0_shap_dependence.png)

## SHAP Decision plots

### Top-10 Worst decisions (Fold 1)
![SHAP worst decisions from fold 1](learner_fold_0_shap_worst_decisions.png)
### Top-10 Best decisions (Fold 1)
![SHAP best decisions from fold 1](learner_fold_0_shap_best_decisions.png)

[<< Go back](../README.md)
