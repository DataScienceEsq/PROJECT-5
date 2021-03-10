# PROJECT-5

Credit Card Churn Prediction

Credit Card Customer Data with features such as Age, Gender, Credit Limit and so on is used by Machine Learning and Deep Learning to classify each credit card customer as one who retains the use of their credit card (0) or does not (1). That way one is able to predict the attrition rate among current credit card customers. This is a supervised or labeled classification problem.

Next we drop the label column in the data and use unsupervised clustering techniques to create two different clusters of Credit Card Customers ... one who retain the use of their credit card and the other that do not.

The following files are included in this repo. Each file will need the CSV file BankChurners.csv to run them in a PYTHON environment:

(a) CreditCardChurnMLMODEL.ipynb: Uses Supervised Machine Learning Models to Classify Customers between 0 and 1 as defined above. This file uses PANDAS dataframes and associated algorithms.

(b) CreditCardChurnDLMODEL.ipynb: Uses Supervised Machine Learning Models to Classify Customers between 0 and 1 as defined above. This file uses PANDAS dataframes and associated Keras Deep Learning algorithms having a TensorFlow backend.

(c) CreditCardChurnPySparkMLModel.ipynb: Uses Supervised Machine Learning Models to Classify Customers between 0 and 1 as defined above. This file uses SPARK dataframes and associated algorithms.

(d) CreditCardChurnPySparkDLMODEL.ipynb: Uses Supervised Machine Learning Models to Classify Customers between 0 and 1 as defined above. This file uses SPARK dataframes and associated Keras Deep Learning algorithms having a TensorFlow backend.

(e) CreditCardChurnPySparkMLClustering.ipynb: Uses Unsupervised Machine Learning Models to Cluster Customers in k = 2 clusters between those who keep using their credit cards and those who do not. This file uses SPARK dataframes and associated algorithms such as K-Means etc. Note: The label column is removed from the dataframe to allow for clustering.

Note: The above files may need to be downloaded in raw format before being uploaded to a Jupyter Notebook.
