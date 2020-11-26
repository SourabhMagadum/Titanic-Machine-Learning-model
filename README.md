# Titanic-Machine-Learning-model
A classification problem related to predicting a passenger's survival in the Titanic sinking disaster. Started the problem by 
viewing, analysing and visualizing the relation and estimated effects of different features with the dependent variable i.e. 
'Survival'. Visualised each variable by means of various graphs like histograms, bar graphs, point plots using matplotlib and 
seaborn libraries. Used feature engineering to complete the train and test dataset by filling the features having missing values with median for numeric datatype and mode for categorical datatype and excluded the features having more than 60-70% missing values or features having negligible importance in the prediction. Then created new features using the combination of two or more features and categorized various features like Name, Age and Fare into different bands using pandas’ qcut () function. Developed and compared different models based on their accuracy scores using different classification algorithms like Logistic Regression,Decision tree, KNN, SVM, Naive Bayes, Random Forests. An accuracy score of 78.5% was finally obtained using Random Forest based model.

