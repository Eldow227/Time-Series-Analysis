In this repository You can find projects of time series analysis.

## Net Value of Microsoft

In this project I managed to predict future value of MIcrosoft net. The data I was working on you can find in txt file called net_value. I uploaded this file because I don't know when you visited this repository, and the data could have changed since that time.
In this project I try basic ARMA model, but I use AUTO ARIMA to find optimum. As it turnes out, WSL estiamtor is much better for this problem, so I created a function called auto_reg which changes the estimator to WLS.
I wrote Python code in google colaboratory (jupyter notebook) so you can run it by yourself any time you want.
In case you had some problems with loading data in jupyter you can also upload it by yourself from your computer.

## EBITDA of Microsoft

Here I tried to predict EBITDA of MIcrosoft. 
Code in this one is very similar to Net Value project.



## Is Melbourne good for selling solar energy ? - Time Series analysis using ARIMA model

This one is one of datacamp contest subject. I took part in it, unfortunetly I didn't finish. I decided for it because I think subjects like this are very interesting, I managed to create a model, but I am not sure about it's accuracy.

COMMENT:

In my projects I often used the same functions and code as in previous. In this case I think about auto_reg function, which changes the estimator and code cell when I replace outliers. So please don't be surprised if some columns seems to look excatly the same as in previous project.
