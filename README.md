# kaggle-titanic

This is Python code for [my attempts](https://www.kaggle.com/hodapp)
at the [House
Prices](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/leaderboard)
beginner competition on Kaggle.

This contains:

- A `shell.nix` to set up a Python environment with scikit-learn,
  matplotlib, numpy, Jupyter, and some associated dependencies.
- A Jupyter notebook for loading the data, doing some exploratory
  analysis, transforming some features, and evaluating some models
  based on Lasso, Ridge, xgboost, and random forests (as well as
  ensembles based on these).  If you run this notebook from start to
  finish, it will train these models and produce a CSV suitable for
  submission to Kaggle, in addition to many pages of other graphs and
  tables.
