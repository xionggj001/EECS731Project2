# EECS731Project2
Analyzing Shakespeare Play data set downloaded from https://www.kaggle.com/kingburrito666/shakespeare-plays.

This project contains two parts. The first part mainly focuses on analyzing the data set by pandas. We count the number of different plays, the number of players in each play, the number of playlines of each player in each play and etc. 

The second part focuses on the classification of player based on the features in other columns. We propose four diffirent models to do this classification task. 
There is a challenge for this task is the string data in most columns of this data set. So we first convert those string data into int data. We propose to transfer the playline into the number of words  and average number of characters in each word for each player. 

The first model is decision tree. 
The second model is random forrest.
The third model is support vector machine.
The fourth model is non-bayesian regressor.

As the simulation shows, random forrest achieves the best performance at a classification rate of 0.65 and non-bayesian regressor achieves the worst performance at a classification rate of 0.05. We also found that support vector machine with linear kernel cannot be applied to multi-group classification problme. 

For the details, please refer to the code. 
