# term-deposit-logistic-regression
This is an example on how to implement logistic regression to predict wheather a client will subscribe to a term deposit as a result of direct marketing campaigns (phone calls). The dataset if from the UIC Machine Learning Repository.
imported all the required packages 
uploded the csv file i have uploded the whole file in github
i have taken data from gkrishna9790 its an excelent dataset 
about the data set - it is the dataset of people opting for term deposit or not with many x variable columns like age marital status job gender etc
delet all the null indexes present in the data set
now doing eda (exploratory data analysis) as the education index needed it 
now plotting many crossplot like y and age , y and job , y and marital status , y and education 
note = here y is the dependent varaible on which we are predicting or it is the 0 , 1 values where 1 means the person has a term deposit after connecting to them and 0 means it does not buys the term deposit eveny after call connect
creating dummy variables as there are many columns with values which are categorical which needs to be changed in numeric form 
now using ref (recursive feature elimination) which helps in selecting the most important column it works with using logistic regression and then finding outh the column with most weight or imp and it repeats until the desired no of imp columns does not meet for furthure clarity visit the code
now building the logistic regression model in this split the data into test and train 30% test and 70% train 
after using the predict function we came across with the 90% accuracy which is preety good
now ploting the roc curve and aur value which acutaly gives how good our model is 
