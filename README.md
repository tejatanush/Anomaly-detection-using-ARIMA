# Aomaly-detection-using-ARIMA
Anomaly detection using an ARIMA model involves fitting the model to historical time series data to predict future values. The model's residuals (differences between actual and predicted values) are then analyzed. Anomalies are identified by setting a threshold, often based on standard deviations of these residuals. Data points where residuals exceed this threshold are considered anomalies. This approach is useful for detecting significant deviations from the expected pattern, such as unexpected spikes or drops, and can help in identifying unusual events or errors in the data.
### Features 
Import Libraries                                                                                       
Import Dataset                                                                                         
Check for stationarity                                                                                 
Import auto arima                                                                                      
Split into Training and Test set                                                                       
Build an ARIMA model                                                                                   
Predict results for test dataset                                                                      
Plot predictions and true values                                                                      
Evaluate metrics                                                                                      
Set Threshold to detect anomalies                                                                     
Plot Anomalies                                                                                        
### Applications 
* ARIMA models can be used to detect unusual transactions or account activity by identifying 
  deviations from normal spending patterns, helping to prevent fraud in banking and financial 
  services.
*  In cybersecurity, ARIMA models can monitor network traffic data, detecting anomalies such as 
   unusual spikes in traffic that could indicate potential security breaches or attacks.
*  In industrial settings, ARIMA models can analyze sensor data from machinery to detect anomalies, 
   allowing for early prediction of equipment failures and reducing downtime through preventive 
   maintenance.
  ## Compiler Type:  
  I used a compiler GPU provided in google colab while running this project.
  ## References  
[daily-website-visitors](https://www.kaggle.com/datasets/bobnau/daily-website-visitors)
  ## Requirements  
Pandas  
Numpy  
Matplotlib  
pmdarima
## Programmes  
Python  
## Owner  
[Teja Tanush](https://github.com/tejatanush) 
