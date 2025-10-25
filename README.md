# Credit-Risk-and-Portfolio-Performance-Analytics
This project's objective is to develop and validate a predictive model that estimates the probability of loan default for individual borrowers, enabling data-driven credit risk assessment and portfolio segmentation for better lending decisions.

## Methodology
1. Data Preparation: Cleaned and standardized the bankloans.csv dataset, removing 450 missing default values and normalizing numeric variables using StandardScaler. <br>
2. Exploratory Analysis: Used Seaborn visualizations to study relationships between age, income, and debt-to-income ratio, revealing stable financial patterns across age groups. <br>
3. Model Building: Developed three classifiers: Random Forest, SVM, and Logistic Regression, to predict loan default likelihood. <br>
4. Model Tuning: Applied GridSearchCV for SVM hyperparameter optimization and 10-fold cross-validation to ensure robustness. <br>
5. Model Evaluation: Selected Logistic Regression as the final model (Accuracy = 83.6%, ROC-AUC = 0.91, Cross-validated AUC = 0.83), confirming strong predictive performance. <br>
6. Validation & Risk Analysis: Performed fairness checks across education groups and segmented borrowers into 10 risk deciles, verifying that higher predicted PDs corresponded to higher actual default rates. <br>

## Main results
1. Model Performance: Logistic Regression outperformed other models with ROC-AUC = 0.91, accuracy = 83.6%, and cross-validated AUC = 0.83. <br>
2. Fairness: Predicted defaults across education levels closely matched actual defaults — no major bias detected. <br>
3. Portfolio Segmentation: Borrowers grouped into 10 deciles showed a clear increasing trend in both predicted and actual default rates, validating model reliability. <br>
4. Business Implication: The model effectively distinguishes high-risk and low-risk borrowers, allowing for smarter credit approval, risk-based pricing, and capital allocation decisions. <br>
