# Predicting heart disease using Machine Learning

A machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

* Problem definition
* Data
* Evaluation
* Features
* Modelling
* Experimentation

## 1. Problem Definition

In a statement,

Given cliical parameters of a patient, can we predict whether or not they have heart disease?

## 2. Data

Data obtained from the Cleavland data from the UCI Machine Learning Repository. https://archive.ics.uci.edu/ml/datasets/Heart+Disease
## 3. Evaluation

If we can reach 95% accuracy in predicting whether or not a patient has heart disease during the proof of concept, we will pursue the project

## 4. Features

Create data dictionary

* age- age in years
* sex- (1 = male; 0 = female)
* cp- chest pain type
* trestbps- resting blood pressure (in mm Hg on admission to the hospital)
* chol- serum cholestoral in mg/dl
* fbs- (fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)
* restecg- resting electrocardiographic results
* thalach- maximum heart rate achieved
* exang- exercise induced angina (1 = yes; 0 = no)
* oldpeak- ST depression induced by exercise relative to rest
* slope- the slope of the peak exercise ST segment
* ca- number of major vessels (0-3) colored by flourosopy
* thal- 3 = normal; 6 = fixed defect; 7 = reversable defect
* target- 1 or 0

### Preparing the tools

The following tools are going to be used for data analysis, manipulation and modelling:

* pandas
* matplotlib
* numpy
* scikit-learn

