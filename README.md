# Data Science Project: Heart Disease Prediction

## Introduction
This project uses data from the Kaggle, a popular data science web-based platform.    
The data set: [Predicting Heart Disease Using Clinical Variables](https://www.kaggle.com/datasets/thedevastator/predicting-heart-disease-risk-using-clinical-var)    
In brief, it's a 270-Patient Dataset with 13 independent Variables by [Robert Hoyt MD](https://data.world/rhoyt)    

## Dataset and the Variable
This dataset provides **13 independent attributes**, the following description is modified from the [Column part](https://www.kaggle.com/datasets/thedevastator/predicting-heart-disease-risk-using-clinical-var/data)
and [University of California Irvine data repository ](https://archive.ics.uci.edu/ml/datasets/Heart+Disease)
| Variable      | Type of the Variable | Categorical detail  | Description |
| :---   | :---   | :---    | :---   |
| Age	|Numeric | N/A |The age of the patient. |
| Sex	|Categorical | 1 = male; 0 = female|The gender of the patient. |
| Chest pain type	| Categorical | 1: typical angina; 2: atypical angina; 3: non-anginal pain; 4: asymptomatic| The type of chest pain experienced by the patient.|
| BP	| Numeric | N/A |The resting blood pressure level of the patient in mm Hg. |
| Cholesterol	|Numeric | N/A |The serum cholesterol level of the patient in mg/dl. |
| FBS over 120	| Categorical |1 = true; 0 = false| The fasting blood sugar test results > 120 mg/dl. |
| EKG results	| Categorical |0: normal; 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV); 2: showing probable or definite left ventricular hypertrophy by Estes' criteria|The electrocardiogram results of the patient. |
| Max HR	| Numeric | N/A |The maximum heart rate levels achieved during exercise testing. |
| Exercise angina	| Categorical |1 = yes; 0 = no|The patient experienced angina during exercise testing. |
| ST depression	| Numeric | N/A |The ST depression induced by exercise relative to rest on an electrocardiogram. |
| Slope of ST	| Categorical |1: upsloping; 2: flat; 3: downsloping|The slope of the peak exercise ST segment electrocardiogram readings. |
| Number of vessels fluro  |  Numeric | N/A |The number of major vessels (0-3) colored in fluoroscopy images. |
| Thallium  | Categorical |3 = normal; 6 = fixed defect; 7 = reversable defect|The Thallium Stress test findings. |
| Heart Disease	| Categorical |0: < 50% diameter narrowing; 1: > 50% diameter narrowing|Diagnosis of heart disease (based on angiographic disease status) |

## Requirements
In this project, following libraries are used:
- Jupyter Notebook
- Matplotlib
- Numpy
- Pandas
- Scikit-learn
- Seaborn

## License
This project under an open-source MIT license. The data set belongs to the owner [Robert Hoyt MD](https://data.world/rhoyt)
