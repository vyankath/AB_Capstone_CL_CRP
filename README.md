# AB_Capstone_CL_CRP
This study uses a dataset from Framingham, Massachusetts, to predict if a patient has a 10-year risk of coronary heart disease (CHD). To start, I handled missing data, especially in columns like smoking, blood pressure, BMI, glucose, age, etc. These factors were found to greatly impact heart health. I also balanced the class distribution using techniques like SMOTE.

Then, I built several models like Logistic Regression, Support Vector Machine (SVM), Neural Network, Random Forest, and XGBoost. SVM with polynomial and radial-based kernels showed good results, but Random Forest and XGBoost performed even better.

Conclusively, XGBoost outperformed the other models. So, I'm choosing XGBoost as the best model for predicting cardiovascular risk. This model can be valuable for future risk predictions.