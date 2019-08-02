# Graduate-Admission-Predictor
A linear regression model that gives the percentage estimate of getting admitted at a university. 
```
Author - Atharva Pusalkar
Date created - 2nd August 2019
Library used - scikit-learn
Number of train examples - 500
Input data features -
    GRE score  |  TOEFL score  |  University rating  |  SOP rating  |  LOR rating  |  CGPA  |  Research
    0-340         0-120           1-5                   1-5            1-5            0-10     0/1
Output - Probability of getting admitted(0.00 - 1.00).
```

Test-case

```
•Input-
GRE score - 330
TOEFL score - 109
University rating - 5
SOP rating - 4
LOR rating - 4
CGPA - 9.0
Research - 1

•Output-
Probabilty - 83.36%
```
Dataset can be downloaded from here - https://www.kaggle.com/mohansacharya/graduate-admissions/activity
To load the dataset, unzip the downloaded file and run the preprocessing code cell.
