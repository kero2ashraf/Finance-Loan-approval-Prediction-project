# Finance-Loan-approval-Prediction-project

In this project as a summary i am talking about finance loan approval means that if we have a bank and we want money we talk a loan and the bank appove it.

columns : Loan_ID	Gender	Married	Dependents	Education	Self_Employed	ApplicantIncome	CoapplicantIncome	LoanAmount	Loan_Amount_Term	Credit_History	Property_Area	Loan_Status


python packages :

1) numpy
2) pandas
3) matplotlib.pyplot
4) seaborn
5) from sklearn.model_selection import train_test_split
6) from sklearn.impute import SimpleImputer
7) from sklearn.tree import DecisionTreeClassifier
8) from sklearn.model_selection import cross_val_score
9) from sklearn.metrics import accuracy_score,f1_score,confusion_matrix
10) pandas_profiling for summarize the data and giving report


questions : 
1) Give an overview about the data?
2) by using pandas_profiling get the report about the data like missing values and its percentages , visualizations?
3) Make subplots between categorical columns and its counts ?
4) Make subplots between numerical columns and its counts ?
5) Make subplot about gender and its count?
6) Make subplot about married  and its count?
7) Make subplot about dependents and its count?
8) fill the missing values by using simple imputer with the mean and train the imp by fitting the x_train ?
9) transform the x_train by using simple imputer?
10) Train the model by using decision tree ?
11) Get the training accuracy and the validation mean F1 score and accuracy ?
12) Get the max depth of the tree and visualize it?
13) Make a confusion matrix about the predicted data?
