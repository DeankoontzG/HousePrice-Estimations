# HousePrice-Estimations

This repository contains the different models I trained and tested as part of a Kaggle competition focused on housing price prediction. It contains the different models I tested.

## 🧠 Models Used

### 1. Linear Regression
Simple regression model, tested first on all available features (after having transformed textual data into numerical data), then refined and optimized.

**Optimization strategy:**  
Comparing the accuracy of trained models using different combinations of the most significant features (filtered using regression coef).
 However, as expected, the model's accuracy remained limited due to irrelevant and highly inter-correlated features — violating the assumption of feature independence.

### 2. RVM Model (Radial Basis Function-based)
Works better as the amount of non significant and inter-correlated Features allows for maximal dimension reduction without impacting data significance.
I tuned the model by varying the dimensionality reduction settings and observing changes in prediction accuracy.

## ✅ Next Steps
- Introduce cross-validation to better evaluate model performance and improve model selection during optimization steps.


