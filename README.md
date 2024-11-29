# Machine Learning Project - Dropout Prediction in MOOCs

## Project Overview
This project focuses on predicting student dropouts in Massive Open Online Courses (MOOCs) by measuring a variety of different demographic, engagement, and academic performance features. Manage and predict using various machine learning algorithms whether a student will drop or pass a course, what key factors lead to dropouts, and measure the performance of various machine learning models in order to choose the best one.

## Dataset
Contains anonymized student data that includes:
* **Demographics**: Gender, region, age band.
* **Academic History**: Number of previous attempts, highest education level.
* **Engagement Metrics**: Studied credits, click counts on the platform.
* **Outcome**: Final result (Pass or Withdrawn).

## Preprocessing Steps 
1. **Management of Missing Values**:
   - Numeric columns: Mean-filling 
   - Categorical columns: Mode-filling.
2. **Feature Scaling**: 
   - Applied StandardScaler for normalization.
3. **Encoding**: 
   - One hot encoding for categorical variables. 
4. **Class Imbalance**: 
   - Addressed using oversampling methods.

## Machine Learning Models
The following algorithms were trained and evaluated.
1. Logistic Regression
2. Gaussian Naive Bayes
3. Support Vector Machine (SVM)
4. Random Forest
5. MLP
6. Gradient Boosting
7. XGBoost

## Model Evaluation
* Metrics Used: Accuracy, Precision, Recall, F1-Score and ROC curve.

## Conclusion

From the perspective of dropout prediction, the project exemplifies how machine learning, feature engineering and algorithm selection are important. The results shows that approaches like class imbalance and engagement with the courses improves the accuracy and XGBoost proved to be the most effective model.
