# Xgboost

## Core Data Structure

xgboost.DMtrix(data, label=None, feature_names=None, feature_types=None)

- feature_names: get feature names (column labels)
- feature_types: get feature types(column types)
- get_float_info(): get float property from the DMatrix
- get_label(): get the label of the DMatrix
- num_col(): get the number of columns (features) in the DMatrix
- num_row(): get the number of rows in the DMatrix.

## Learning API

xgboost.train(params, dtrain, num_boost_round=10, evals=(). obj=None)
