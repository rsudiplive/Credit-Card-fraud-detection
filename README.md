# Credit-Card-fraud-detection
Our goal is to identify fraudulent credit card transactions!

The datasets contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 98 frauds out of 56,962 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 2% of all transactions.

It contains only numerical input variables which are the result of a PCA transformation. 
Also, understood the use and benefits of using different random sampling(over & under sampling) techniques to balance out both the classes. Also tried applying SMOTE (Synthetic Minority Oversampling Technique) with the concept of k-nearest neighbors and generating synthetic data between the choosen point and neighbors. Performed implementing SMOTE with other classification models and finding out the best model with the best set of hyperparameters.

The dataset has been collected and analysed during a research collaboration of Worldline and the Machine Learning Group (http://mlg.ulb.ac.be) of ULB (Université Libre de Bruxelles) on big data mining and fraud detection. Performed some automatic anomaly detection techniques for outlier removal using Local Isolation forest, LOF(Local Outlier Factor) and OneClassSVM to detect the frauds in a credit card transaction.

Finally, trying out implementing SMOTE with Deep Neural Network to create a sequencial model using keras and fitting the model. Plotted the train and validation Learning Curves to diagnose model learning performance over experience/time, representing whether a model is a good fit or not. 
