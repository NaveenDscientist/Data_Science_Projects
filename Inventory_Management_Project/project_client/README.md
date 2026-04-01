## Inventory Forecasting for JIT Optimization

This project aimed to build a predictive model to help a service center move toward **Just-In-Time (JIT)** inventory management. The objective was to accurately predict demand patterns so that the organization can:

* Reduce stock-out risk
* Avoid overstock situations
* Optimize working capital
* Improve operational efficiency

Using historical service records such as:

* Invoice Date
* Job Card Date
* Vehicle Model
* Current KM Reading
* Service Description

We performed:

* Data Cleaning
* Feature Engineering
* Handling Missing Values
* Class Imbalance Treatment (SMOTE)
* Feature Selection
* Hyperparameter Tuning
* K-Fold Cross Validation
* Multi-Metric Model Comparison

Four classification models were developed and tuned:

* Logistic Regression
* Random Forest
* XGBoost
* Gradient Boosting

After evaluating models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC, the best-performing model was selected based on highest **F1-score and Recall**, which are critical for JIT inventory systems.

The final model is suitable for production deployment and can significantly reduce stock mismanagement risks.
