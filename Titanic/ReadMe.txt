Steps:

1. Run Data_train and Data_test to create the Processed\Simple Folder which will contain the data that is preprocessed.
2. Run Model.ipynb which performs the prediction for survived using the XGBoost Classfier.
3. Run Data_train_OneHot and Data_test_OneHot to create the Processed\One-Hot Folder which will contain the data that is preprocessed.
3. Change the import directory to the One-Hot Folder in order to import the one-hot encoded data for the model.