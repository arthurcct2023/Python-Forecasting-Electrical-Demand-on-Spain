🎯 Auto regressive analysis to forecast electricity demand in Spain in a window of 2 months performing Mean Absolute Percentage Error (MAPE) of 8% using Unobserved Component Model.

🔑 Forecasting electricity demand is an essential and challenging step for modelling energy systems and transition. A demand higher then production could lead to blackouts whereas a the opposite could lead to waste of energy and overloading of transmission lines. 

🧠 In this project patterns are analysed in the electricity demand in Spain, unvailing daily, weekly and yearly seasonalities. 
Once seasonalities are identified, autoregressive models such as Holt-Winters Exponencial Smoothing, SARIMAX and Unobserved Component Model are applyed to forecast electricity demand in Spain in a window of 2 months.
While baselines for the problem perform with around 14% MAPE, Unobserved Component Model imputed with seasonalities identified is able to forecast the demand with 8% MAPE.
Improvements on the model are believed to be possible adding external information from weather, which is unavailable on the dataset used.
