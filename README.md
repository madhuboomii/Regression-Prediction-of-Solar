
LINEAR REGRESSION:
   Linear regression is a statistical method for modeling relationships between a dependent variable with a given set of independent variables.
   Simple linear regression is an approach for predicting a response using a single feature.
   In order to provide a basic understanding of linear regression, we start with the most basic version of linear regression, i.e. Simple linear regression. 
# REGRESSION-PREDICTION-OF-SOLAR:
   I'm predict Solar Dataset using Simple Linear Regression:
START:
   I get dependent variable is Temperature columns
   and independent variable is Humidity columns.
   Then unwanted coulums are deleted using DROP key.
   locate and reshape the values of X and Y.
   Then using the MatPlotLib to visible a Scatter plot of X,Y.
   split the values of x and y using train & test methods.
   Thus the simple linear regression was implemented.
RESULT:
   Temperature is increasing andso Humidity is decreasing.
   Then using sklearn find the mean squard error and mean absolute error.
          [mean_squared_error(y_test,y_predict)=632.8442776309752]
          [mean_absolute_error(y_test,y_predict)=21.277420254964497].
LOOKER STUDIO:
   I'm also predict the same data set in looker studio
   Using table to visible a colums of Temperature,TimeSunRise and timeSunSet. 
   Then select the Bar chart put in  x axis=Time and y axis=Temperature.
   Then select the Donut Chart calculte the percentage of Temperature.
   Finally select the Gauge to find the Speed.
