### Personal Learning Playground for Anomaly Detection

**S5 - A Labeled Anomaly Detection Dataset, version 1.0(16M)**

From Yahoo's description of the dataset: 
> "[...] The goal of this dataset is to benchmark your anomaly detection algorithm. The dataset consists of real and synthetic time-series with tagged anomaly points. The dataset tests the detection accuracy of various anomaly-types including outliers and change-points. The synthetic dataset consists of time-series with varying trend, noise and seasonality. The real dataset consists of time-series representing the metrics of various Yahoo services."

**yahoo.ipynb**  
Experiments with a simple threshold model, as well as model saving/loading/benchmarking using the MLflow model registry.  
(Best result 0.887 AUC)

**yahoo_de-season.ipynb**   
All the above, plus an attempt at automatically finding and removing seasonality using acf + median sampling  
(Best result 0.952 AUC)

**yahoo_FFT.ipynb**  
Threshold model with de-seasoning by removing dominant frequencies (FFT)  
\*(Best result **0.989 AUC**)\*