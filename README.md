# Demand Forecast
Context:

In the context of an industry-leading electricity distribution company, there exists a pressing need to gain insights into the anticipated electricity demand for the upcoming 1-2 years. This understanding is critical for effectively managing electricity production and coordinating with vendors. The precision of demand estimation is pivotal in ensuring that the electricity procurement or production aligns seamlessly with the expected demand.

Data Preparation:

The dataset utilized in this project was sourced from Kaggle and underwent a meticulous cleaning and preprocessing phase using Pandas. Feature engineering was employed to generate additional variables, including year and month, enhancing the dataset's richness.

Model Development:

For forecasting, the chosen model is an ARIMA (Autoregressive Integrated Moving Average) model, implemented with the statsmodels library in Python. The model underwent training on a historical dataset encompassing energy consumption in terawatts per month, spanning from 1973 to 2019. The selection of the model involved a thorough evaluation of the AIC (Akaike Information Criterion) and BIC (Bayesian Information Criterion) for various parameter combinations.

Outcomes:

The forecast model demonstrated a commendable accuracy of 98%, gauged through the mean absolute percentage error (MAPE) on a holdout dataset. Visual representations comparing the forecasted consumption against the actual consumption were crafted using Matplotlib, providing a comprehensive view of the model's performance.





