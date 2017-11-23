# Pollution-Peaks
Predict pollution peaks in Nantes (France) from open data (R)


## Table of Contents

1 Data preparation<br>
...1.1 Preparation of weather data<br>
...1.2 Create dataframe<br>
......1.2.1 Load data<br>
......1.2.2 Perform date transformations<br>
......1.2.3 Calculate daily averages of weather data<br>
......1.2.4 Load dataMeteo and give proper class to dates and proper names<br>
......1.2.5 Load holidays' dates<br>
...1.3 Feature engineering<br>
......1.3.1 Weekdays<br>
......1.3.2 Holidays<br>
......1.3.3 Traffic (days when people go to and return from holidays)<br>
......1.3.4 Pollution<br>
2 Split the dataset<br>
3 Exploratory data analysis<br>
...3.1 Check missing values<br>
...3.2 Decomposition of the time series<br>
......3.2.1 Check plots<br>
......3.2.2 Create a time series object<br>
......3.2.3 Decomposition of the series<br>
...3.3 Visualize relationships<br>
......3.3.1 Check correlations among variables<br>
......3.3.2 Temperature<br>
......3.3.3 Cloudiness<br>
......3.3.4 Wind<br>
......3.3.5 Rain<br>
......3.3.6 Traffic<br>
4 Regularized linear regression (coming soon)<br>
5 ARIMA<br>
...5.1 Preliminar checks<br>
......5.1.1 Stationarity<br>
......5.1.2 Plot ACF/PACF charts<br>
......5.1.3 Differencing the original non-stationary data<br>
...5.2 Build models<br>
......5.2.1 Quick and dirty<br>
......5.2.2 Add seasonality (with Fourier terms)<br>
...5.3 Add regressors<br>
6 Artificial Neural Networks (feed forward network)<br>
...6.1 Build models<br>
......6.1.1 Quick and dirty<br>
......6.1.2 Add seasonality (with Fourier terms)<br>
......6.1.3 Add regressors<br>
7 Compare models' performances<br>
8 Walk Forward Validation<br>
9 Going further
