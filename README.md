# Credit_Risk_Analysis

### Overview of the analysis:
The purpose of this analysis was to utilize what we learned in Chapter 17 regarding Machine Learning to help Jill with a credit-risk model. Using imbalanced-learn and the scikit-libraries, we were able to build and evaluate six different machine learning models. 

We were provided with a dataset in the form a CSV file, titled "LoanStats_2019Q1." This data included, but was not limited to, the following information about loan applicants: loan amount, term, interest rate, emploloyee title, length of employment, home ownership status, annual income, purpose, and credit scores.

After evaluating the six models, the goal was to determine whether it could be used to evaluate credit risk.

### Results:
The balanced accuracy score (true positive+true negative / total results), the precision (true positive/actual results), and the recall scores (true positive/predicted results) of all six machine learning models are shown below.

<u>Oversampling</u>
![image](https://user-images.githubusercontent.com/88783255/146696303-5daad8d2-8c5f-46c8-8c72-6d398e9b99c8.png)

<u>SMOTE Oversampling</u>
![image](https://user-images.githubusercontent.com/88783255/146696328-e1b6cd19-5a67-4276-84df-218c61037187.png)

<u>Undersampling</u>
![image](https://user-images.githubusercontent.com/88783255/146696359-0fedc231-0926-47a5-bc4b-f0aac198b8e2.png)

<u>Combination Sampling</u>
![image](https://user-images.githubusercontent.com/88783255/146696379-72e013df-f66c-476f-a068-34dd8de18bd3.png)

<u> Balanced Random Forest Classifier </u>
![image](https://user-images.githubusercontent.com/88783255/146696886-8a23163e-cf4d-43bf-9650-8b9bf37f9885.png)


### Summary:
As shown above, the accuracy of all of these models appears to be weak (60-70 range). Additionally, the precision is very low for all of the models outputs shown above. 
