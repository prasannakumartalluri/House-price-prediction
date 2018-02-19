# House-price-prediction
Algorithm Devolopment:
In this project we are going to use Python programming language to develop the code for our project
Data Analysis:
   Creating a machine learning model using random forest to analyze the relationship between SalePrice and other 79 independent variables.
  Random Forest:
Random forest is part of ensemble learning for machine learning techniques like classification, regression and other tasks.
To predict the price of each home first we will construct the decision trees using random forest technique. Each decision tree is constructed by using a random subset of the training data. After training the forest, we can then pass each test row through it, in order to output a prediction. This technique can give accurate predictions and runs efficiently on large data, and consist of following steps:
1.	Pick random K data points from the data set
2.	Build the Decision tree associated to these K data points.
3.	Choose the number Ntree of trees to be built and repeat steps 1&2.
4.	For new data point, make each of Ntree trees predict the value of Y to for the data point in problem, and assign the new data point the average across all the predicted Y values.

Advantages:
•	This algorithm can solve both the machine learning problems I;e classification & regression.
•	It is accurate when huge population of data is missing and it is good in estimating missing data.

Disadvantages:
•	It gives good results to classification problems compared to regression.
•	In regression problems it cannot predict beyond the range in the training set.

Expectation from results:
With 80 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa, the project goal is to predict the final price of each home.
The dataset I’m using in this project lends itself to advanced machine learning techniques like random forests and gradient boosting.
