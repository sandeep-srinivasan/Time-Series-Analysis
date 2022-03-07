# Time-Series-Analysis

# Time series of the wind speed

The time series plot of the Hurricane Wilma on 23rd October 2005 is plooted below,

![image](https://user-images.githubusercontent.com/42225976/157121462-98d3c9c0-085b-4abb-92ac-abb325e4968c.png)

The time series plot fitted with a non-linear regression line is,

![image](https://user-images.githubusercontent.com/42225976/157122313-2cd4b26b-f0f5-4d50-bf3e-59ab3486f512.png)

Plot of the residual series with a horizontal line at y=0 is,

![image](https://user-images.githubusercontent.com/42225976/157122385-ef36e37d-5c40-4dc4-ab08-162d6d9a9835.png)

The equation of the line is, y = 3.934e+00 - 2.973e-01 x + 2.412e-02 x^2 - 3.911e-04 x^3

Plot of the acf function of the residuals is,

![image](https://user-images.githubusercontent.com/42225976/157122511-16b8f325-b204-4978-bb09-7f6b2c959329.png)

Plot of the differenced series, correcting the time scale is,

![image](https://user-images.githubusercontent.com/42225976/157122566-dd2fd256-0aa1-4a0a-b75e-8e77df831553.png)

Plot of the acf function of the differenced series is,

![image](https://user-images.githubusercontent.com/42225976/157122619-c62ce88c-0d5e-43dd-9cfd-08053c6b15d1.png)

Plot of the twice differenced series, again correcting the time scale is,

![image](https://user-images.githubusercontent.com/42225976/157122666-4bd4f063-f52b-488c-b6db-675acd95f099.png)

Plot of the acf function of the twice differenced series is,

![image](https://user-images.githubusercontent.com/42225976/157124020-569176fe-d5c5-44be-8baf-829ff64cc06a.png)

Plot of the smoothed series using a simple moving average with q = 1 is,

![image](https://user-images.githubusercontent.com/42225976/157124136-433f35a3-c9e8-48a3-9ef6-ad935fcc9f74.png)

Plot of the smoothed series using a simple moving average with q = 2 is,

![image](https://user-images.githubusercontent.com/42225976/157124197-9a041212-f80a-4cbc-9bbe-529989c2d922.png)

Plot of the smoothed series using a simple moving average with q = 10 is,

![image](https://user-images.githubusercontent.com/42225976/157124521-544c874c-7d7c-4b65-8d18-6a1594bc6ccc.png)

Plot of the smoothed series using a simple moving average with q = 50 is,

![image](https://user-images.githubusercontent.com/42225976/157124596-7b62af11-5509-4ef8-8a94-0e61b60a0c39.png)

It can be seen from the graphs that increasing the value of ‘q’ increases the smoothing effect and we get a better time series curve. But as you increase ‘q’ there will be loss of data and information because of lesser number of data points in the curve.

# Classical Decomposition Algorithm (CDA) upon a time series 

Performed the classical decomposition algorithm (CDA) upon a time series of monthly temperatures recorded in Columbus, OH from January 1995 to December 2005. The units of measurement is Fahrenheit. The plot of this time series is,

![image](https://user-images.githubusercontent.com/42225976/157125857-3d9fa2a8-fd9c-490b-8da6-e2eca6013fc0.png)

Plot of the time series with the overlay of the smoothed plot using Moving Average is,

![image](https://user-images.githubusercontent.com/42225976/157125993-fe2db98c-4d8a-40fe-93b1-949ee8d222fc.png)

Plot of the residuals by year is,

![image](https://user-images.githubusercontent.com/42225976/157126137-21e2d5a6-4620-4390-b321-8a6e277ef4d7.png)

Plot of temperatures by month in a panel of size 3 rows by 4 columns is,

![image](https://user-images.githubusercontent.com/42225976/157126345-83cc65ad-04cf-426d-acb1-167a5f158445.png)

Plot of the estimate of the seasonal component is,

![image](https://user-images.githubusercontent.com/42225976/157126478-973fe5c7-cb32-4bc7-8751-8fea1090f0d1.png)

Plot of the deseasonalized time series and estimation of the trend parametrically is,

![image](https://user-images.githubusercontent.com/42225976/157126591-3c9af4ff-cf02-474e-aefc-230263a0ef76.png)

Plot of the series and the estimated regression line is,

![image](https://user-images.githubusercontent.com/42225976/157126634-87e44fac-f463-4c60-98ea-49acc4b009a2.png)

Plot the residual series with a horizontal line at y=0 is,

![image](https://user-images.githubusercontent.com/42225976/157126702-d1a4c6e7-1f92-4f34-8266-038aeeb11cae.png)

Plot of the acf is,

![image](https://user-images.githubusercontent.com/42225976/157126750-7f6537e9-15c9-485b-a3a3-fc6fe126e062.png)

Carrying out the Ljung-Box test and the Q-Q plot of the residuals is,

![image](https://user-images.githubusercontent.com/42225976/157126810-418f3ad7-47ad-452f-a9ab-3262307abccd.png)

From the plots of ACF for different lags, we can see that by increasing sigma_w^2 , the ACF decreases since the ACF and the value of sigma_w^2 are inversely proportional which is shown below,

![image](https://user-images.githubusercontent.com/42225976/157127174-becfebf3-c222-40e4-8c59-857f8bde0fb2.png)

![image](https://user-images.githubusercontent.com/42225976/157127152-4e88535a-19ae-48ca-a8e1-57a4696b349e.png)
