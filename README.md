# Credit_Risk_Analysis
In this project, I will be using Machine Learning models on the credit card credit dataset from LendingClub (a peer-to-peer lending services company) to precict Credit Risk. Machine Learning models used include;

* Logistic Regression
* Balanced Random Forest
* EasyEnsemble

Re-Sampling Techniques such as;

* Oversampling( RandomOversampler & SMOTE)
* Undersampling (ClusterCentroids).

I also utilized metrics such as Balance Accuracy Score, Classification Report and Confusion Matrix to acsertain the suitability of these algorithms to the dataset.


# RESOURCES

* Python
* Jupyter Notebook
* LoanStats_2019Q1 (CSV)

# RESULTS

# 1.  Balanced RandomForest

<img width="790" alt="Screenshot 2023-02-09 at 12 42 10 AM" src="https://user-images.githubusercontent.com/109445468/217729691-b9d31534-97eb-4f0b-b577-963d7c9a6f9a.png">

<img width="790" alt="Screenshot 2023-02-09 at 12 42 33 AM" src="https://user-images.githubusercontent.com/109445468/217729702-0a5e919c-6b95-4b1b-bdd2-37f3c5a3c522.png">

* Accuracy Score - 0.78
* Precision for Good Application - 0.99
* Precision for Bad application - 0.04
* Recall for Good Application - 0.90
* Recall for Bad Application - 0.66
* F1 Score - 0.95
* Total occurence of Good Application - 17,118
* Total Occurence of Bad Application - 87


# 2. Easy Ensemble Classifier

<img width="790" alt="Screenshot 2023-02-09 at 12 43 24 AM" src="https://user-images.githubusercontent.com/109445468/217729724-8def87c1-333c-475e-b4f4-824bec60b7c4.png">

<img width="790" alt="Screenshot 2023-02-09 at 12 44 11 AM" src="https://user-images.githubusercontent.com/109445468/217729744-2aa02de4-9493-4f27-a617-58674e01aed3.png">

* Accuracy Score - 0.93
* Precision for Good Application - 0.99
* Precision for Bad application - 0.07
* Recall for Good Application - 0.94
* Recall for Bad Application - 0.91
* F1 Score - 0.97
* Total occurence of Good Application - 17,118
* Total Occurence of Bad Application - 87

# 3. Random Oversampling

<img width="790" alt="Screenshot 2023-02-09 at 12 44 51 AM" src="https://user-images.githubusercontent.com/109445468/217729754-683f5558-d314-490f-b6b6-2948ab806401.png">


<img width="790" alt="Screenshot 2023-02-09 at 12 45 12 AM" src="https://user-images.githubusercontent.com/109445468/217729762-6a3b4704-2257-44f3-8c43-c067dbb46942.png">

* Accuracy Score - 0.65
* Precision for Good Application - 0.99
* Precision for Bad application - 0.01
* Recall for Good Application - 0.68
* Recall for Bad Application - 0.61
* F1 Score - 0.81
* Total occurence of Good Application - 17,118
* Total Occurence of Bad Application - 87

# 4. SMOTE Oversampling

<img width="790" alt="Screenshot 2023-02-09 at 12 45 36 AM" src="https://user-images.githubusercontent.com/109445468/217729767-07cd23ad-c3bf-44aa-8e9a-75087fbdecc8.png">
<img width="790" alt="Screenshot 2023-02-09 at 12 59 18 AM" src="https://user-images.githubusercontent.com/109445468/217730639-6abaecb4-3657-42e2-818f-23f0cb32e605.png">

* Accuracy Score - 0.62
* Precision for Good Application - 0.99
* Precision for Bad application - 0.01
* Recall for Good Application - 0.58
* Recall for Bad Application - 0.57
* F1 Score - 0.73
* Total occurence of Good Application - 17,118
* Total Occurence of Bad Application - 87

# 5. UnderSampling
<img width="844" alt="Screenshot 2023-02-09 at 1 33 15 AM" src="https://user-images.githubusercontent.com/109445468/217736263-584c41a4-53fb-4fab-a57c-df6859d0f45d.png">

* Accuracy Score - 0.62
* Precision for Good Application - 0.99
* Precision for Bad application - 0.01
* Recall for Good Application - 0.57
* Recall for Bad Application - 0.45
* F1 Score - 0.61
* Total occurence of Good Application - 17,118
* Total Occurence of Bad Application - 87

# 6. SMOTEENN
<img width="866" alt="Screenshot 2023-02-09 at 1 33 58 AM" src="https://user-images.githubusercontent.com/109445468/217736240-e2990381-903e-4d14-a99c-ded4a09322ae.png">

* Accuracy Score - 0.64
* Precision for Good Application - 0.99
* Precision for Bad application - 0.01
* Recall for Good Application - 0.70
* Recall for Bad Application - 0.58
* F1 Score - 0.73
* Total occurence of Good Application - 17,118
* Total Occurence of Bad Application - 87

# Summary

<img width="790" alt="Screenshot 2023-02-09 at 12 42 53 AM" src="https://user-images.githubusercontent.com/109445468/217729711-c1878e2f-cc6c-4b6b-9380-c1321f70ba34.png">

We rated all the variables to determine the most important variables that determine credit risk.

<img width="790" alt="Screenshot 2023-02-09 at 12 43 24 AM" src="https://user-images.githubusercontent.com/109445468/217729724-8def87c1-333c-475e-b4f4-824bec60b7c4.png">

* With an accuracy score of 0.93, Easy Ensemble Classifier is the best model for preventing fraudulent loan applications.
