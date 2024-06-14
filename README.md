# diabetics_prediction_by_naive-bayes
Using the Machine Learning Algorithm Naive Bayes for diabetics prediction 
In this project the data set taken is the diabetic data of the patients consisting of the continous independent variables with the dependent categorical varible 
so the Logistic regression with naive bayes is used for solving the problem
the data set provided consists of 
1. Preganancies - Number of times the patient got pregnant 
2. Glucose - Plasma glucose concentration 
3. Blood Preassure - Diastolic Blood Preassure (mmHg)
4. Skin Thickness - Triceps skin fold thickness (mm)
5. Insulin - 2-Hour serum insulin (mu U/ml)
6. BMI: Body mass index (weight in kg/(height in m)^2)
7. DiabetesPedigreeFunction: Diabetes pedigree function
8. Age: Age (years)
9. Outcome: Class variable (0 or 1)

So in the project the null values were detected first then treated by substituting with the Median as it is not effected by the outliers. then the outliers were detected by the use of Box plots and are treated by substituting these lower level and upper level outlier with the 5th and 95th percentile respectively. But the Skin and Insulin again substituted with 0.21 and 0.80 percentiles then the visuaLization was performed to detect the prediction rate and finally the prediction model is executed by using GuassianNB 
