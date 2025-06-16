Time Series Projects (Bachelor’s Edition)
I’ve worked on two time series forecasting projects around Microsoft’s financials as part of my Bachelor’s degree. Both use real-world data and Python notebooks in Google Colab—so you can easily run, tweak, and experiment with the code yourself.

1. Net Value Forecast for Microsoft
What I did:

Objective: Predict Microsoft’s future net value.

Data: Everything’s in a net_value.txt file—that way, even if the original data changes, you’ll still get the same numbers I used.

How:

Started with a simple ARMA model.

Switched to auto_arima to find the best parameters automatically.

Noticed that Weighted Least Squares (WLS) gives better results, so I built a helper function (auto_reg) to plug it in.

How to run it: Just open the notebook in Google Colab. If the data doesn’t load automatically, upload net_value.txt manually—it’s included in the repo.

2. EBITDA Forecast for Microsoft
This one’s basically the same setup, but with a different target: Microsoft’s EBITDA (Earnings Before Interest, Taxes, Depreciation, and Amortization). I applied the same ARMA/ARIMA process and the WLS-adjusted auto_reg function for consistency and improved accuracy.


