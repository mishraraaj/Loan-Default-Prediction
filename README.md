# Loan-Default-Prediction

Problem Statement Desciption - Lending Club is the world’s largest online marketplace connecting borrowers and investors. An inevitable outcome of lending is default by borrowers. The idea of this project is to create a predictive model that identifies applicants who are relatively risky for a loan. 

## Missing Value Imputation Using Knn imputer
Imputation for completing missing values using k-Nearest Neighbors.Each sample’s missing values are imputed using the mean value from n_neighbors nearest neighbors found in the training set. Two samples are close if the features that neither is missing are close.

# Conclusion

The last_fico_range, grade, inq_last_6month features were found to be the most relevant for predicting loan default in. The current model tries to predict default biased data from credit analysts grade and assigned interest rate. . The XGB and Rf models provide substantial improvements on traditional credit screening. A recall score significantly and robustly above 90%, with AUC-ROC scores ≃74%. The features provided to the model in our study generalize to any lending activity and institution, beyond P2P lending. The present work could, therefore, be augmented in order to predict loan default risk without the need for human credit screening.
Only the Random Forest., XGBoost, model is used, but there are many good ones out there even neural networks. The models can also be improved further by finer tunings on hyperparameter.
In the bank loan behaviour prediction, for example, banks want to control the loss to a acceptable level, so they may use a relatively low threshold. This means more customers will be grouped as “potential bad customers” and their profiles will be checked carefully later by the credit risk management team. In this way, banks can detect the default behaviours in the earlier stage and conduct the corresponding actions to reduce the possible loss.
