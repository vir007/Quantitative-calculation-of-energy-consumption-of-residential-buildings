# Quantitative calculation of energy consumption of residential-buildings
- Utilizing machine learning methods to estimate the EPB of buildings

## Goal
- Predict Heating Load and Cooling Load

## Input Parameters
- Relative compactness
- Surface area
- Wall area
- Roof area
- Overall height
- Orientation
- Glazing area

## Output Parameters
- Heating Load
- Cooling Load

## Requirements
- Numpy
- Pandas
- Sklearn
- Matplotlib

## Results
- For Heating Load

Algorithm |	Accuracy | ( STD)
--- | --- | ---
LiR	| 0.892809 | (0.064143)
Ridge	| 0.888898 | (0.073554)
Lasso	| 0.739750 | (0.185156)
ElasticNet |	0.751113 | (0.184069)
Bag_Re |	0.969104 | (0.082573)
RandomForest |	0.968549 | (0.084006)
ExtraTreesRegressor |	0.968994 | (0.082331)
KNN |	0.885004 | (0.194983)
CART |	0.968717 | (0.082255)
SVM |	0.837300 | (0.149457)

- For Cooling Load


Algorithm | Accuracy | ( STD)
--- | --- | ---
LiR	| 0.876337 | (0.033166)
Ridge	| 0.870432 | (0.036123)
Lasso	| 0.751754 | (0.101792)
ElasticNet |	0.762353 | (0.098235)
Bag_Re |	0.963511 | (0.023490)
RandomForest |	0.963513 | (0.024185)
ExtraTreesRegressor |	0.950593 | (0.022661)
KNN |	0.924107 | (0.088863)
CART |	0.955078 | (0.021109)
SVM | 0.859163 | (0.076793)



