# Human-Resource-Department-using-Data-Science
# Source: https://www.udemy.com/course/data-science-for-business-6-real-world-case-studies/
# Data Source: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset/data

Human Resource Department using Data Science. Performing Logistic Regression, Random Forest Classifier, and Artificial Neural Networks

The HR team collected extensive data on their employees and approached you to develop a model that could predict which employees are more likely to quit. 
The team provided you with an extensive data, here's a sample of the dataset: 
JobInvolvement
Education
JobSatisfaction
PerformanceRating
RelationshipSatisfaction
WorkLifeBalance. etc...

Using **Logistic Regression, Random Forest Classifier and Artificial Neural Networks** I've Developed an AI model to Reduce hiring and training costs of employees by predicting which employees might leave the company.

**Confusion Matrix:** A confusion matrix is a table used in machine learning and statistics to assess the performance of a classification model. It summarizes the results of classification by showing the counts of true positive, true negative, false positive, and false negative predictions.

**A confusion matrix is used to describe the performance of a classiﬁcation model: **

**True positives (TP)**: cases when classiﬁer predicted TRUE (they have the disease), and correct class was TRUE (patient has disease). 
**True negatives (TN):** cases when model predicted FALSE (no disease), and correct class was FALSE (patient do not have disease). 
**False positives (FP) (Type I error):** classiﬁer predicted TRUE, but correct class was FALSE (patient did not have disease). 
**False negatives (FN) (Type II error):** classiﬁer predicted FALSE (patient do not have disease), but they actually do have the disease
**Classiﬁcation Accuracy** = (TP+TN) / (TP + TN + FP + FN) 
**Precision** = TP/Total TRUE Predictions = TP/ (TP+FP) (When model predicted TRUE class, how often was it right?) 
**Recall** = TP/ Actual TRUE = TP/ (TP+FN) (when the class was actually TRUE, how often did the classiﬁer get it right?)


**F1 Score**

**F1 Score = 2*(Precision*Recall)/(Precision+Recall)**
**F1 Score = 2(TP)/(2TP + FP + FN)**

F1 Score is an overall measure of a model's accuracy that combines precision and recall. 
F1 score is the harmonic mean of precision and recall. 
Difference between F1 Score and Accuracy? 
In unbalanced datasets, if we have large number of true negatives (healthy patients), accuracy could be misleading. Therefore, F1 score might be a better KPI to use since it provides a balance between recall and precision in the presence of unbalanced datasets. 
