# Spam_Message_Classifier
#This model has 97% accuracy in classifying spam emails.
#As the dataset has large number of input columns, I have used a dimensionality reduction algorithm known as PCA to only use those columns on which out output depends on the most.
#Before sending the data to PCA algorithm I have used a Scaler which will centre everything aroung the origin.
#After finding the usefull columns i passed them to Logistic Regression and calculated the accuracy score which is >97%.
#To Perform standardization,PCA and Logistic Regression in order and in one go I created a pipeline too.
#In the other file I found the appropriate principle components by plotting the cumsum of variance ratio.
