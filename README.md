# Stroke Prediction using Machine Learning

This project aims to predict the likelihood of a stroke using machine learning models. The focus is on comparing model performance and selecting the most suitable model for a medical use case.


## Project Description

In this project, a healthcare dataset related to stroke prediction was used. Two machine learning models — Logistic Regression and Random Forest — were trained and evaluated.

The main objective was not just to achieve high accuracy, but to determine which model performs better in identifying actual stroke cases.



## Dataset

* Healthcare Stroke Prediction Dataset
* Contains features such as:

  * Age
  * BMI
  * Average glucose level
  * Hypertension
  * Heart disease
  * Smoking status


## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Imbalanced-learn (SMOTE)


## Models Used

### Logistic Regression

* Applied with class balancing
* Performs well in identifying stroke cases

### Random Forest

* Ensemble learning model
* Achieves higher overall accuracy


## Methodology

* Data cleaning (removed unnecessary columns, handled missing values)
* One-hot encoding for categorical variables
* Feature scaling using StandardScaler
* Handling class imbalance using SMOTE
* Train-test split (80-20)
* Model training and evaluation


## Results

| Model               | Accuracy | Observation                               |
| ------------------- | -------- | ----------------------------------------- |
| Logistic Regression | ~75%     | Better at detecting stroke cases          |
| Random Forest       | ~92%     | Higher accuracy but poor stroke detection |


## Conclusion

Although the Random Forest model achieved higher accuracy, it was not effective in identifying actual stroke cases.

Logistic Regression, despite having lower accuracy, performed better in detecting stroke patients. In medical applications, identifying true positive cases is more important than overall accuracy.

Therefore, Logistic Regression is the more suitable model for this problem.
