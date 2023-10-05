# CodeClauseInternship_Breast-Cancer-Classification


## Dataset Link: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/data

## Problem Statement:

To classify whether the existing tumor is benign or malignant.


## Attribute Information:

ID

Diagnosis (M or B) - M: Malignant, B: Benign

Radius - mean of distances from center to points on the perimeter of each cell nucleus

Texture - standard deviation of gray-scale values

Perimeter

Area

Smoothness - local variation in radius lengths

Compactness - (perimeter^2/area - 1.0)

Concavity - severity of concave portions of the contour

Concave Points - number of concave portions of the contour

Symmetry

Fractal Dimension - (coastline approximation - 1)

{Each of the above 10 attributes have a mean value, standard error value and a 'worst' or largest (mean of the three largest values) of these features}

# Workflow:
#### 1) Data Collection
#### 2) Data Visualization (EDA)
#### 3) Data Preprocessing
  **Data Cleaning:** Handle missing values, Remove duplicates.

  **Data Transformation:** Encode categorical variables

  **Handling Outliers:** Identify and handle outliers in the data.

   **Correlation Analysis:** Check for correlations between features.
#### 4) Splitting the data into dependent and independent variables
#### 5) Feature Scaling
#### 6) Train_Test_split
#### 7) Model Training
-- Logistic Regression
-- Decision Tree
-- Random Forest
-- KNN Classifier
#### 8) Building predictive model / Model Testing
