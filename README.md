Regression-for-Numeric-Data

In this task, I have to perform linear regression with different methods on simulation based generated dataset. I used the given parameters to generate the dataset. 
Data Visualization
 
a) - In this task, sklearn linear regression model is used to train generated data and once the model is train, predict function is used to make prediction. The result shows that linear regression model does not perform well on nonlinear data. 
Mean Squared Error: 0.005950213308862813
Prediction Curve
 
b) - In this task, I applied the polynomial feature with degree of 2 on x_data , with that I convert original features into higher order term to fit linear regression on nonlinear data. sklearn linear regression model is used to train generated data and once the model is train, predict function is used to make prediction. The result shows that linear regression with high order perform well on nonlinear data.
 Mean Squared Error: 0.0005085916255709522
Prediction Curve
 
c) - In this task, I used sklearn to define Deep Neural Network DNN model with 3 layers includes input later with 1 feature, hidden later with 6 neurons and relu activation function and output layer with 1 neuron.  I split the data into 80 20 percent for training and testing respectively. 
Mean Squared Error: 0.0005900024867407085
Training Loss Curve
 
