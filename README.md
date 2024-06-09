Wine Dataset from UCI:
Usage of PCA to get better results while predicting the cultivar type(1,2 or 3) from the chemical components as features.
The supervised model used to predict after carrying out PCA was logistic regression.

Banking Dataset:
PCA was used to reduce dataset size as 4900 features were present,by plotting scree plots and using explained variance metric,we used only the first 300 principal components to predict the amount of money transacted,thereby greatly reducing training time.The RMSE of the model was also given significant attention to account for the accuracy-time trade off.
