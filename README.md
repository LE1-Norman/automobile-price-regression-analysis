# automobile-price-regression-analysis
ML model to predict car prices based on features like brand, model, year, Engine HP, etc. Implements linear regression, LASSO-regression, RIDGE-regression.  Includes EDA, feature engineering and model comparison.

The goal of this project is to identify the main factors that influence the cost of cars and create an accurate tool for estimating market prices. We will use linear regression and regularization techniques (Lasso and Ridge) to develop a model that will allow us to fairly evaluate the value of vehicles.

Data source:  https://www.kaggle.com/datasets/CooperUnion/cardataset

Size: 11914 lines, 16 features

Результаты:

Модель	| MAE: |	MSE: |	RMSE: |	R^2: |

Linear regression |	13,371 |	1,072,853,156 |	32,754 |	0.6645 |

LASSO-regression  |	13,568 |	1,113,505,251 |	33,369 |	0.6518 |

RIDGE-regression  |	13,209 |	1,105,779,249 |	33,253 |	0.6542 |
