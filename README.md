# Insurance_Fraud_Detection
**OBJECTIVE**: Detecting if an insurance claim was fraudulent or not 

**STRATEGY USED**:
• Using hyperparameter tuning of the two classifiers – Decision tree and Random Forest we try to determine the optimal set of parameters such that the model performs the best.
• Used random and grid search methods for hyperparameter tuning. 
• Experimented k-cross folds cross-validation to train and test the model.

**APPROACH**:
**Step 1**: Read the test and train data. Understand the Understand the dataset by identifying the 
number of columns and rows and datatypes.
Python function used: .info() and .describe()
**Step 2**: Understand the datatype of each column and especially note down the categorical type 
columns.
**Step 3**: As most of ML algorithms cannot handle categorical variables, one hot encoding is used to 
encode the categorical features, except the target column that is to be predicted. The first step is to 
integrate training and test data to maintain uniformity in encoding categorical features.
**Step 4**: Construct a default decision tree classifier and random forest classifier for both data sets and 
obtain an accuracy score for the decision tree.
Perform hyperparameter tuning for the decision tree classifier. The below screenshot represents the 
specific code snippet for hyperparameter tuning for both classifiers for respective datasets.
