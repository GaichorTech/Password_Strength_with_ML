		Password Strength using ML
When a user is trying to sign up for a website it is helpful to provide feedback about the strength of the password he has chosen. 
The goal of this project is to create a model that will help the user know the complexity of the chosen password. 
Machine Learning models do not take text as an input, hence I created character vectors of each password by doing feature engineering. Thus, I transformed the text data into numerical data so that I can train a ML algorithm. Since all the features were numerical I tried Decision Tree, Random Forest and Gaussian Naive Bayes algorithms. Out of the three the first two gave satisfactory results. Since, decision tree is fast in predicting an output, I went with the decision tree model.
