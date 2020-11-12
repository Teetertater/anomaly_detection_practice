### Personal Learning Playground for Anomaly Detection

**S5 - A Labeled Anomaly Detection Dataset, version 1.0(16M)**

From Yahoo's description of the dataset: 
> "Automatic anomaly detection is critical in today's world where the sheer volume of data makes it impossible to tag outliers manually. The goal of this dataset is to benchmark your anomaly detection algorithm. The dataset consists of real and synthetic time-series with tagged anomaly points. The dataset tests the detection accuracy of various anomaly-types including outliers and change-points. The synthetic dataset consists of time-series with varying trend, noise and seasonality. The real dataset consists of time-series representing the metrics of various Yahoo services."

**yahoo.ipynb** contains some experiments with a simple threshold model, as well as model saving/loading/benchmarking using the MLflow model registry.

**yahoo_bonus_eda.ipynb** contains all the above, plus a bit of additional exploratory analysis using time series data transformations