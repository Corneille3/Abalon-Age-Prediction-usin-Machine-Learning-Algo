# Abalon-Age-Prediction-usin-Machine-Learning-Algo
Our goal is to build a regression machine-learning algorithm that will predict the age of the “abalone”. According to Cambridge dictionary, an abalone is a “small sea creature that can be eaten. It lives inside a shell that is the shape of an ear and is white and shiny inside”. A more common name for abalone is “snail”
  The age of an abalone is determine by cutting the shell through the cone, coloring it, and counting the number of rings using a microscope a tedious and lengthy task. Therefore, we will try to automate this process by deploying our model using “flask” framework. By adding 1.5 to the rings feature, we can compute the age of the abalone, in years.
Furthermore, the skill or performance of a regression model must be report as an error in those predictions. This actually makes sense. If we are predicting a numeric value like a height or a dollar amount, we do not want to know if the model predicted the value exactly (which could be intractably difficult in practice); instead, we want to know how close the predictions were to the expected values. That is why our models will evaluated on the basis of errors: 
	Mean absolute error (MAE)
	Mean squared error (MSE);
	r2 score. 
In addition, I will try to convert the problem to classification problem where there will be two class of age: A and B. B representing age between 2.5-10.5 and B the age between 10.5-30.5. 2.5 is the minimum age value and 30.5 the maximum of our target class.
