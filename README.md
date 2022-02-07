# crypto-risk-Week-11
Imports:
1. warnings
2. numpy
3. pandas
4. pathlib
5. collections
6. sklearn
7. imblearn

## Ensemble Learning
- Split data into training and test sets
- Scale data with sklearn StandardScaler (Use x-train scale information on x-test, for fair scaling)
- Use random tree classifier to predict y-test data
- Give reports and feature rankings
- Repeat prediction model with Easy ensemble classifier

## Resampling
- Split data into training and test sets to notice imbalance of classes in y-train
- Scale data with sklearn StandardScaler (Use x-train scale information on x-test, for fair scaling)
- Use logisitic regression to predict classes with no resampling techniques
### Oversampling with logisitic regression applied after
- Naive oversampling
- SMOTE oversampling
### Undersampling with logisitic regression applied after
- Cluster Centroids
### Combination sampling with logisitic regression applied after
- SMOTEENN
