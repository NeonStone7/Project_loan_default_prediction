# L&T Vehicle Loan Default Prediction
## About Dataset
Financial institutions incur significant losses due to the default of vehicle loans. This has led to the tightening up of vehicle loan underwriting and increased vehicle loan rejection rates. The need for a better credit risk scoring model is also raised by these institutions. This warrants a study to estimate the determinants of vehicle loan default. A financial institution has hired you to accurately predict the probability of loanee/borrower defaulting on a vehicle loan in the first EMI (Equated Monthly Instalments) on the due date.






Following Information regarding the loan and loanee are provided in the datasets:
- Loanee Information (Demographic data like age, Identity proof etc.)
- Loan Information (Disbursal details, loan to value ratio etc.)
- Bureau data & history (Bureau score, number of active accounts, the status of other loans, credit history etc.)
Doing so will ensure that clients capable of repayment are not rejected and important determinants can be identified which can be further used for minimising the default rates.
#### Dataset Link: https://www.kaggle.com/datasets/mamtadhaker/lt-vehicle-loan-default-prediction

## About Training
The process started with understanding the features and relationship with the target using various data exploration techniques. Feature Engineering and model selection was done in 4 experiments where each experiment has a different combination of feature engineering, resampling, and feature selection techniques. This led to a total of 6 unique algorithms and 24 trained models.

After initial training, the best two models were selected and ensembled for improved model performance.

Hyperparameter tuning was done using Randomized Search to select the best tuning parameters.

The best experiment preprocessing pipeline was selected to train the final model's preprocessor and the ensemble algorithm was then fitted to the preprocessed data.

