# PySpark-GasPrices

In this project, I have used the power of Apache Spark through the PySpark API. I have analysed gas prices collected by all the stations in France almost daily from 2019 on, approx. **17 milions of rows of data**. 

After some important manipulations and cleaning of the data, as well as creating new features, I have constructed a ML pipeline using the library of PySpark **MLlib**. The models were a Linear Regression and a Random Forest, which performed well on the data; the former obtained a slightly less RMSE compared to the latter.
