# Predictive Model Comparison

## Objective
Compare Linear Regression and Random Forest models to evaluate their ability to predict customer funding amounts and support profit-oriented marketing decisions.

## Model Performance

| Model | Test RMSE |
|---|---:|
| Linear Regression | $9,961.75 |
| Random Forest | $7,667.74 |

Random Forest achieved approximately 23% lower test RMSE than Linear Regression, indicating better predictive accuracy on the evaluated test dataset.

## Business Implications
Lower prediction error can support more informed estimates of customer financial value. However, predictive accuracy alone does not guarantee higher campaign profitability; targeting decisions must also account for customer response probabilities, campaign costs, and expected financial returns.

## Conclusion
Random Forest was selected for the individual-level expected-value targeting strategy based on its stronger test performance. The resulting strategy was evaluated against a segment-based targeting benchmark.

## Limitations
Results are based on the assignment dataset and modeling assumptions. Performance and financial outcomes would require further validation before real-world deployment.
