# Email-Traffic-Prediction
Analysis of time series data has been a challenging research subject for decades. Email traffic has recently been modelled as a time series function using a Recurrent Neural Network (RNN) and RNNs were shown to provide higher prediction accuracy than previous probabilistic models from the literature. Given the exponential rise of email workloads which need to be handled by email servers, in this paper we first present and discuss the literature on modelling email traffic. We then explain the advantages and limitations of different approaches as well as their points of agreement and disagreement. Finally, we present a comprehensive comparison between the performance of RNN and Long Short Term Memory (LSTM) models. Our experimental results demonstrate that both approaches can achieve high accuracy over four large datasets acquired from different universities’ servers, outperforming existing work, and show that the use of LSTM and RNN is very promising for modelling email traffic. 
# Data Source
The datasets were collected from four universities namely Technical University of Crete (TUC), Greece, University of the Peloponnese (UoP), Greece, Murdoch University, Australia and Liverpool John Moores University (LJMU), UK. The email traffic logs were collected for ten non-consecutive weeks from TUC, four consecutive weeks from LJMU, five consecutive weeks from UoP, and fifty-two consecutive weeks from Murdoch university. The datasets consist of spam, system incoming and outgoing and users’ incoming and outgoing email traffic respectively. Workloads are characterized based on temporal dependence and email size. 
# Architecture
![Figure 6 Proposed model architecture](https://user-images.githubusercontent.com/38637722/179386227-fc112ac7-a601-49ca-80c1-29863b730ab6.jpg)
# Tools & Technologies
Machine learning models - ARIMA, SARIMA, KNN, Linear Regression, Random Forest models
Deep learning models - RNN and LSTM models
Language - Tensorflow, keras, python, Matplotlib, Numpy, Pandas
# Final Result
![image](https://user-images.githubusercontent.com/38637722/179386884-ee20617d-fed0-4b04-923f-ec080e9854e7.png)
![image](https://user-images.githubusercontent.com/38637722/179386813-29a990a6-d4c3-47a1-bb26-b9d78bb4894c.png)
![image](https://user-images.githubusercontent.com/38637722/179386830-35e9791f-048a-40a2-bb5b-3cf98bdfb1a4.png)
![image](https://user-images.githubusercontent.com/38637722/179386870-0f4513a8-ba7a-4ee5-a8a9-672e6fee9641.png)
![image](https://user-images.githubusercontent.com/38637722/179386878-64c2a007-6107-448a-a558-0174d05e5d14.png)
# Conclusion
In this work we have focused on the problem of modelling email traffic workloads by treating traffic as a time series function. We have discussed the existing literature and we have used RNN and LSTM models for modelling email traffic gathered from four different universities. We have shown that with the use of appropriate initialization of the training weights, proper activation functions and hyper-parameters the performance of the RNN model can be substantially improved for modelling email traffic. However, the highest accuracy achieved by RNN is smaller for most email traffic categories in our datasets than the performance achieved by LSTM. 
