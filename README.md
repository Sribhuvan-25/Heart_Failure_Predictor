### Heart_Failure_Predictor

- This project is to predict if a patient is prone to a heart failure within their follow up period.
- Data set has been taken from https://www.kaggle.com/andrewmvd/heart-failure-clinical-data.

#### Feature Information
- age -> Age of a person

- anaemia -> Deficiency of red blood cell or hemoglobin (Boolean)

- diabetes -> If a patients is suffering from diabetes (Boolean)

- ejection_fraction -> Percentage of blood pumped out of a filled ventricle with each contraction.

- high_blood_pressure -> If the patient has hypertension (Boolean)

- platelets -> Number of platelets in the person's blood (kiloplatelets/mL)

- serum_creatinine -> Amount of serum creatinine in the blood (micromoles/L)

- serum_sodium -> Amount of serum sodium in the blood (mEq/L)

- sex -> Gender of the person (Boolean)

- smoking -> If the person smokes (Boolean)

- time -> Follow up period (Days)

- DEATH_EVENT -> If the patient dies during the follow up peroid (Boolean)


Built a ML model by testing 8 different classification models - Logisitc Regression, Decision Tree Classifier, Random Forest Classifier, MLP Classifier, Gradient Boosting Classifier, SVC Classifier, Gaussian Naive Bayes, K Nearest Neighbors.

The best score was achieved through Random Forest classifier with an accuracy of 87.7%.


