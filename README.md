# Stroke
Stroke Final Project

Stroke is a disease that affects the arteries leading to and within the brain. It is the No. 5 cause of death and a leading cause of disability in the United States. A stroke occurs when a blood vessel that carries oxygen and nutrients to the brain is either blocked by a clot or bursts (or ruptures).
This project aims to predict the feasibility of suffering a stroke. The dataset has 5110 subjects and 11 variables. 

Four models were used to evaluate this model: Logistic Regression, Decision Tree,Random Forest and MLP Classifier. We had several variables that were highly correlated like age, hypertension, heart_disease,ever_married, avg_glucose, bmi and smoking_status. We also had lots of outliers but only excluded a couple since, for example, it''s actually possible to see really high BMI''s on people who don''t suffer strokes. Therefore, it didn''t seem like the right path.
The dataset was pretty imbalanced. For this, we used the SMOTE function but didn''t see much improvement in the Logistic Regression Model.Then, we chose to remove highly correlated variables but we got pretty similar results in both LR as well as Decision Tree. Decision Tree was the best model but our F1 score for a potential stroke(0.16) wasn''t wonderful either.As for Random Forest and MLP Classifier we had the exact same results as Logistic Regression (no prediction at all for stroke). Therefore, we can conclude that the data used for this project wasn''t enough or maybe there could be other models that could be a better fit for this dataset.


