# Diabetes-Prediction
Predicting whether a patient is diabetic or not based on the few attributes of patient. Predictions are performed using Supervised Machine Learning Techniques.

Attributes of Patient considered for analysis:
A: Number of pregnancies
B: Concentration of plasma glucose in a 2-hour oral glucose tolerance test
C: Diastolic blood pressure - Measured in mmHg
D: Triceps skin fold thickness - Measured in mm
E: Insulin concentration in the serum in 2 hours. Measured in (mu U/ml)
F: Weight in kg/height in (m^2)
G: Function that assigns the probability of someone getting diabetes
H: Age
Target: Value of 0 or 1 corresponds to no diabetes and diabetes

Data Cleaning: 
- values of attributes D,E,F are missing.
- almost 50% of E column data is missing, so the row is removed for analysis.
- the missing rows of D are replaced by the mean and of E by median. 
- the outliers were removed based on the attribute and their relevance.(like blood pressure can never be equal to zero)

Model building:
- KNN regression
- linear regression
- Logistic regression
- Kerenilzed Support Vector Machine (rbf, poly, and linear)
- Decision Tree Model

Prediction:
From the above models, based on train and test scores Logistic regression was apt for making predictions on the test dataset.
