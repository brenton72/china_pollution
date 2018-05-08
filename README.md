# china_pollution

For this project, we will predict daily average PM 2.5 levels in Beijing. Our dataset contains PM 2.5 records from May 2014 to December 2016. 

We test a variety of models:

1) Random Forests regressor
2) LSTM
3) Gaussian Processes

Ultimately, we achieve our best performance when we combine the Random Forests and Gaussian Process models.

Core features included

1) Autoregressive features (PM 2.5 in Beijing at t-1 and t-2 days)
2) PM 2.5 values from other cities (Xi'an, Harbin, Baotou, and Qingdao)
3) Weather (temperature, wind speed and direction, humidity, air pressure)
