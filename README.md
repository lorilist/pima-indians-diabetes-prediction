# pima-indians-diabetes-prediction
**Background:** <br>
In 1988, Smith et al. published 'Using the ADAP Learning Algorithm to Forecast the Onset of Diabetes Mellitus,' a forecast of Diabetes onset for a high risk population of Pima Indian women, age 21+. Given the sample size is small and underlying functional relationship unknown for data features, the researchers believed traditional statistical approaches would yield disappointint results - Instead, the researchers used an early neural network model, ADAP. <br>

In this notebook, we will examine the deidentified study data and build a few models.


**Objective:** <br>
Using baseline data, can you predict whether a woman of Pima Indian heritage will develop Diabetes within 5 years? <br>
Does the resultant model outperform the ADAP model used in the original research?

**About the Data:** <br>
The dataset consists of 8 medical predictors and a target variable, Outcome. Below are data definitions:
* Pregnancies - Number of times pregnant
* Glucose - Plasma Glucose Concentration at 2 hours in an oral Glucose Tolerance Test (GTT)
* BloodPressure - Diastolic Blood Pressure (mm Hg)
* SkinThickness - Triceps Skin Fold Thickness (mm)
* Insulin - 2-Hour Serum insulin (uU/ml)
* BMI - Body Mass Index (Weight in kg/(Height in m)^2)
* DiabetesPedigreeFunction - A custom indicator of diabetes hitory in relatives, built for study
* Age - Age (years)
* Outcome - 1/0 flag indicating whether patient developed Diabetes within 5 years

Predictors are reported as of an initial medical visit. The outcome variable reflects follow-up medical visits in the 5+ years following the initial visit.

**Resources:** <br>
[Kaggle Dataset](https://www.kaggle.com/uciml/pima-indians-diabetes-database) <br>
[Original Research](https://europepmc.org/backend/ptpmcrender.fcgi?accid=PMC2245318&blobtype=pdf)
