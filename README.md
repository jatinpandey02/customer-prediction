# customer-prediction

Logistic Regression model(scikit-learn) and neural net(tf-keras) to predict sale or not.

Lr model gave a stable accuracy of about 72%.
Neural net achieved accuracy of about 80%. It was showing a initial plateau at about 72%. Therfore I used exponential decay 
for learning rate which allowed the model to reduce loss even at a small value without overshooting. Use of tanh showed better 
results than relu in this case which maybe attributed to the classification nature of the problem.
