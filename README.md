# Thyroid-Detection-using-Stacked-Ensemble-technique

Brief about dataset:

Thyroid disease is one of the most difficult diseases to diagnose. It is a condition which causes your thyroid gland to not produce enough of certain crucial hormones. It usually may not cause noticeable symptoms in the early stages and hence becomes extremely difficult to diagnose. Applying Machine learning algorithms can help assist healthcare workers in identifying signs and symptoms based on patterns shown in past cases of patients' data.

Here we will be learning the code and workflow for diagnosing whether or not a person is suffering from Thyroid disease based on Stacked Generalization or Stacking technique.

Problem Statement:

To build a classification methodology to predict the type of Thyroid based on the given training data.

Target Column is given as "Class" column will have four unique values “negative", "compensated_hypothyroid", "primary_hypothyroid", "secondary_hypothyroid”.

Conclusion:

By performing various Data Analysis,we have applied Data-processing.In the model fiting we have passed two base models K-nearest Neighbors and Support Vector Classification. The prediction of both models are stacked to fit in meta model i.e Random Forrest.

Hpyer-parameter tuning is performed on Random Forest Classifier where we are passing best parameters to conclude an Accuracy score of 91.9%

