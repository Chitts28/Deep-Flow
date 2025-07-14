# Deep-Flow
Prediction of bulldozer sale prices was done using a cleaned and merged dataset combining sales and machine info.
After handling missing values with mean, mode, or placeholders, date features were extracted like saleYear and saleMonth to train the model for depreciation/inflation based on its manufactured year.
Target encoding was applied to ModelID, and one-hot encoding and scaling for other categorical and numerical features.
A linear regression and random forest model were trained and evaluated using RMSLE on the validation set and test set.
Final predictions were made on the test set and formatted for submission.
