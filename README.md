# HeartDiseasePredictionRisk

### Project Motivation: 

Coronary Heart Disease (also known as Coronary Arty Disease (CAD)) is a type of heart disease that occurs when the arteries of a heart can’t delivery oxygen due to the buildup in plaque. It is the most common form of heart disease. The standard for detecting or establishing presence of CAD is through invasive coronary angiography. Through this process, a thin tube is inserted into the artery in the wrist or groin. Although, it would be beneficial to have a non-invasive way to detect coronary heart disease. 
This data comes from Robert Detrano from the Cleveland Clinic Foundation. The dataset comprises of 303 observations, 13 features and 1 target attribute.  They include results from non-invasive diagnostic tests, result of invasive coronary angiogram and other patient information needed. This project aims to answer the question: Can we predict heart disease using patient medical data? By applying machine learning techniques to structured patient data, we attempt to create a model that can predict the presence of heart disease without the use of invasive techniques. 

### Dataset: 
Kaggle: https://www.kaggle.com/datasets/aavigan/cleveland-clinic-heart-disease-dataset 
Features: age, sex, cp, trestbps, chol, fbs, restecg, thalach. exang, oldpeak, slope, ca, thal, num 
Target: num - target variable which is diagnosis of heart disease through angiographic disease status

### Methodology 
1. Data Preprocessing
   Handling missing values
   One hot encoding
   Scaling Features
2. Model Building
   Logistic Regression  
3. Evaluation
   Accuracy
   Precision, Recall, F1-Score
   ROC-AUC Curve

### Results
The heart disease prediction model achieved an overall accuracy of 87% on the test set. The precision for predicting heart disease was 88%, and the recall was 82%, resulting in an F1-score of 85% for the positive class. The model also demonstrated strong overall performance with a ROC AUC score of 0.95, indicating excellent capability to distinguish between patients with and without heart disease. Based on the confusion matrix, most patients were correctly classified, with minimal false positives and false negatives. These results show that patient medical data can reliably predict the presence of heart disease with high confidence.

### Conclusion 
We demonstrated that patient medical data can effectively predict heart disease with some accuracy. Future work could include hyperparameter tuning, ensemble methods, and deep learning techniques.




