# Sample Datasets
The collection of open datasets for testing.

## housing.csv: The Boston Housing Dataset
The Boston Housing Dataset is a derived from information collected by the U.S. Census Service concerning housing in the area of Boston MA. The following describes the dataset columns:

CRIM - per capita crime rate by town

ZN - proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS - proportion of non-retail business acres per town.

CHAS - Charles River dummy variable (1 if tract bounds river; 0 otherwise)

NOX - nitric oxides concentration (parts per 10 million)

RM - average number of rooms per dwelling

AGE - proportion of owner-occupied units built prior to 1940

DIS - weighted distances to five Boston employment centres

RAD - index of accessibility to radial highways

TAX - full-value property-tax rate per $10,000

PTRATIO - pupil-teacher ratio by town

B - 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town

LSTAT - % lower status of the population

MEDV - Median value of owner-occupied homes in $1000's

## iris.csv: The Iris Dataset
The Iris dataset was used in R.A. Fisher's classic 1936 paper, The Use of Multiple Measurements in Taxonomic Problems, and can also be found on the UCI Machine Learning Repository.It includes three iris species with 50 samples each as well as some properties about each flower. One flower species is linearly separable from the other two, but the other two are not linearly separable from each other.The columns in this dataset are:

Id

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

Species

## lung_cancer.csv: Lung Cancer Dataset
The Lung Cancer Risk Factors Dataset is a comprehensive collection of attributes related to individuals, aiming to explore potential factors associated with the occurrence of lung cancer. The dataset encompasses demographic information, lifestyle choices, and health indicators, providing a valuable resource for researchers and data scientists interested in understanding and predicting lung cancer risks.

Attributes:

GENDER: Indicates the gender of the individual (M for Male, F for Female).

AGE: Represents the age of the individual, contributing to the analysis of age-related patterns.

SMOKING: Reflects the smoking habits of individuals, categorized to capture various levels of smoking intensity.

YELLOW_FINGERS: Describes the presence of yellow fingers, potentially associated with lifestyle choices or health conditions.

ANXIETY: Measures the anxiety level of individuals, offering insights into the psychological aspects of health.

PEER_PRESSURE: Indicates the influence of peer pressure on lifestyle choices.

CHRONIC DISEASE: Highlights the presence or absence of chronic diseases, a crucial health factor.

FATIGUE: Reflects the level of fatigue experienced by individuals, providing information on overall health.

ALLERGY: Indicates the presence or absence of allergies, potentially relevant to respiratory health.

WHEEZING: Describes whether wheezing is present, a symptom often associated with respiratory issues.

ALCOHOL CONSUMING: Indicates the alcohol consumption habits of individuals, which can impact overall health.

COUGHING: Represents the occurrence and severity of coughing, a respiratory symptom.

SHORTNESS OF BREATH: Indicates the presence or absence of shortness of breath, another respiratory indicator.

SWALLOWING DIFFICULTY: Describes difficulties in swallowing, potentially linked to respiratory or other health concerns.

CHEST PAIN: Indicates the presence or absence of chest pain, a symptom associated with various health conditions.

LUNG_CANCER: The target variable, specifying whether the individual has been diagnosed with lung cancer (YES or NO).

This dataset serves as a valuable resource for predictive modeling, exploratory data analysis, and research into the potential risk factors contributing to lung cancer. Researchers can leverage this dataset to uncover patterns, develop models, and advance our understanding of the complex relationships between lifestyle choices, health indicators, and the likelihood of developing lung cancer.

## titanic.csv: Titanic Survival Prediction Dataset
Predict survival on the Titanic and get familiar with ML basics.

Attributes:

survival - Survival. (0 = No, 1 = Yes)

pclass - Ticket class. (1 = 1st, 2 = 2nd, 3 = 3rd)

sex - Sex.

Age - Age in years.

sibsp - # of siblings / spouses aboard the Titanic	

parch - # of parents / children aboard the Titanic	

ticket - Ticket number.

fare - Passenger fare.

cabin - Cabin number.

embarked - Port of Embarkation.	(C = Cherbourg, Q = Queenstown, S = Southampton)


## wine_qt.csv: Wine Quality Dataset
Wine Quality Prediction (Classification Prediction). This data frame contains the following columns.

Input variables:

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

Output variable:

12 - quality (score between 0 and 10)