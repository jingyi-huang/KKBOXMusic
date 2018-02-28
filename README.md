we attempt to do KKBOX music recommendation challenge on the Kaggle in this project. 
The challenge asks for predicting the chances of a user (with or with- out playing history) listening to a song repetitively after the  rst observable listening event within a time window was triggered. 
This problem has implications for customized music recommendation. 
The input for our project is a list of song characteristics and user demographics. 
We then use several machine learning algoithms (Logistic Regression,Decision tree, LightGBM) to output the probability of a user returning to listen the same song again after the  rst observable listening event within a month. 
This challenge is evaluated on area under the ROC curve between the predicted probability and the observed target.