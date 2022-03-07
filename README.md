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
