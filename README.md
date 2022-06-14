Problem Statement:
 This dataset comes from the UCI repository of machine learning databases.The task is to predict if an individual's 
 annual income excceds $50,000 based on census data.
 Data link:http://www.cs.toronto.edu/~delve/data/adult/desc.html
Steps for solving the Data Science Problem:
1. Get the basic understanding of each feature,data types, how many data

2. Exploratory Data Analsis:
   i) Check for output class Distribution to decide the data is balanced or not
	 ii) Check for the missing values
	 iii) Classify the type of variable : 
                                  i) Categorical Variable
                                 ii) Numerical Variable-> Discrete Numerical Varible
                                                       -> Continuous Numerical Variable
  iv) Check the Cardinality(No. of features) of Categorical Variable
   v) Check for duplicate rows or data points
   vi) Data Visualization :
                          i) Bar chart for Independent feature
                         ii) Bar chart for Categorical variable 
                        iii) Bar Chart for Discrete Numerical Variable
                         iv) Distribution/Histogram plot for countinuous variable 
                          v) Box plot for Continuous varible

 3. Feature Engineeirng  :
                          i) Treating Duplicate rows if any
                         ii) Treating  Missing Values
                        iii) Treating Outliers
                         iv) Convert the categorical variable to numerical data 
                          v) Split the data into train and test or cross val set. X_train,y_train,X_test,y_test
                         vi) Feature Scaling
                        vii) If Data is imbalanced- i) Use oversampling technique


 4. Feature Selection: i)By using Information gain(Mutual Information)


 5. Model Building:
                          i) Apply machine learning algorithm i.e Logistic Regression and Random Forest classifier 
                         ii) Evaluate the model based on - Precision, Recall and F1 Score by varying various parameter 
                             and hyperparameter.
                        iii) Draw visualization curve for evaluation metrics for different parameters and hyperparameters.
                        iv) Draw ROC Curve and calculate AUC Score
