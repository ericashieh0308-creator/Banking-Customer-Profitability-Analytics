# Analytical Workflow

## 1. Business Objective
Identify a more profitable customer targeting strategy for a financial institution operating under a fixed marketing budget.

## 2. Data Exploration
Analyze 30,000 historical campaign records to understand customer response behavior and funding outcomes. Evaluate targeting opportunities across 100,000 prospective customers.

## 3. Predictive Modeling
Compare Linear Regression and Random Forest models for predicting funding amounts. Evaluate performance using test RMSE.

| Model | Test RMSE |
|---|---:|
| Linear Regression | $9,961.75 |
| Random Forest | $7,667.74 |

Random Forest achieved approximately 23% lower test RMSE.

## 4. Expected Value Analysis
Estimate customer-level expected financial value using predicted response probabilities, predicted funding amounts, and the $1.50 contact cost.

## 5. Budget Optimization
Rank prospective customers by estimated financial value and select the top 10,000 customers within the $15,000 marketing budget.

## 6. Strategy Comparison
Compare individual-level predictive targeting with segment-based targeting.

- Segment-based projected net profit: $127,275.50
- Individual-level projected net profit: $140,398.32
- Projected improvement: 10.31%

## 7. Business Recommendation
Prioritize individual-level expected-value targeting under the modeled assumptions, subject to further validation before implementation.

## Limitations
The results are model-based estimates, not realized financial returns. Prediction error, assumptions about customer behavior, and differences between historical and future customers may affect actual outcomes.
