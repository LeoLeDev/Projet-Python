# Projet-Python
We analysed a data set that represents 10 years (1999-2008) of clinical care at 130 US hospitals for diabetic encounters.​
We did data analysis, data visualisation and then machine learning
Shape ​:
- 50 columns​
- 101766 rows​
- 0 null value​
The 50 columns will describe the type of patient, type of stay, the laboratory tests performed, the medications admninistered​
The data have different dtypes: int64 or object.​
The null-values are replaced by « ? »​

We first did data analysis and adata visualisation of the features, and went on to do machine learning, to try and predict whether a patient was going to be readmitted or not.
For this we had the column 'readmitted that has 3 different values:​
No readmission;​
A readmission in less than 30 days (this situation is not good, because maybe your treatment was not appropriate);​
A readmission in more than 30 days (this one is not so good as well the last one, however, the reason can be the state of the patient.​
We then used a few ML algorithms to predict values and got a result up to 0.69 accuracy with the Random Forest algorithm, after applying grid search.

For future researches, it might be interesting to use these results to try and predict which treatment might be more efficient depending of the other features.

​

​

​
