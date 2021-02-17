# Credit_Risk_Analysis

* Overview of Loan Prediction Risk Analysis
Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

* Language/Technology
Jupiter Notebook, CSV & Scikit package

* Data Sources and Coding File
We used the included link to download the Module-17-Challenge-Resources.zip.  This file includes the LoanStats_2019Q1.csv dataset and two starter code files: credit_risk_resampling_starter_code.ipynb and credit_risk_ensemble_starter_code.ipynb

* Analysis Methodology
We are to properly define the purposese, ensure the balanced accuracy score and the precision and recall scores for ALL SIX algorithms are described.  

* Results
Data Rollup
Please find results of 6 different models employed
![summary](https://github.com/basecipher/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

The top 10 features contributing to the model are shown below:
![top 10](https://github.com/basecipher/stock-analysis/blob/main/Resources/VBA_Challenge_2018.png)

* Summary
The results are to be summarized with no specific recommendation on using the a particular model as all 6 models are good at predicting low risk loans.  The issue is that none are extremely effective at predicting high risk loans which was the purpose of this development process.

* Final Recommendation
The study sheds light to the fact that we must continue to running the the model even further and at each stage sticking with no more than the top 10 influencing features while disregading all other features from model.  This will allow a more accurate result which will render the purpose of this development process.
