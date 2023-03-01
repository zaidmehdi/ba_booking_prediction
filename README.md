# ba_booking_prediction
Predicting the buying behavior of British Airways customers.  
This jupyter notebook contains the work that I have done for the second task of the Data Science certificate offered by The Forage Work Experience with British Airways. The goal is to build a classification model that predicts whether a customer will complete the booking of a flight or not.  
The final model selected was a CatBoost with parameters: {'reg_lambda': 0.001, 'learning_rate': 0.01, 'iterations': 250, 'depth': 8}.  
The recall on the test set was: 0.780  
The accuracy on the test set was: 0.691
