# Author : Uchenna Emechebe
# Date 20th July 2017

# This is a Kaggle Competition from Mercedes benz that ran from May 30th 2017 to July 3rd 2017
# I stumbled into this competition on the 20th of June 2017 as my first Kaggle competition.

# Purpose: Use various features of various mercedes benz cars to predict the time each car will spend 
# on the test bench before it passes testing. This might help reveal features that lead to faster testing times
# and thus save the company money by not spending so much money on unneccessary features that does not help
# and also , maybe, help with thier scheduling times. 

# The challenge posed by this  data set is that it has lots of features (377 features); a mixture of
# categorical and continous data. 


# Files in order of analysis of data

# 1_ProcessingTrain_Test_Data.ipynb : This was where I processed the data

# 2_Train_Common_FeatureSelectionWithLasso.ipynb : This is where I used lasso regularisation as a model selection tool

# 3_ModelBuilding_95Features_GBregression.ipynb : Using the 95 features selected and gradient boost regressor, I built models
