# Diamond-Price-Predictor-Using-Machine-Learning-
This project uses machine learning to predict the price of diamonds. The model was trained on a dataset of almost 54,000 diamonds. The model was able to predict the price of diamonds with an accuracy of 98%. <br>
The dataset is acquired from Kaggle. <br>
Link to dataset: https://www.kaggle.com/datasets/shivam2503/diamonds <br>


Trained Models <br>
The following models were trained on the dataset: <br>

Ridge <br>
LinearRegression <br>
Lasso <br>
ElasticNet <br>
SVR <br>
KNeighborsRegressor <br>
RandomForestRegressor <br>
PCA <br>
XGBRegressor <br>
Libraries Used <br>
The following libraries were used in this project: <br>

pandas <br>
numpy <br>
matplotlib <br>
seaborn <br>
sklearn <br>
Conclusion <br>
Random Forest and XGBoost gave us the best R2 score at 0.98. This means that 98% of the variability observed in price can be explained by these two models, which is fairly good. However when you compare RMSE scores between these two models, XGBoost gave us a lower (although only slightly) RMSE score 382.2 compared to 383.8. Therefore, we can conclude that the best model to predict the prices of diamonds is XGBoost with a polynomial feature degree of 1.
