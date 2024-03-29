# ML model on Covid-19 ventilator control problem
Author: [Ng Zheng Jue](https://github.com/xinjue37), [Ong Ming Jie](https://github.com/ethanong98), [Chiam Yu Wei](https://github.com/yuwei0410), [Lim Yi Jing](https://github.com/yijing0612), [Cheng Hung Xu](https://github.com/hxDying)

* This is a project developed in undergraduate Year 2 - Semester 1.
* This repository consists of **solving time-series data forecasting problem** on the [Kaggle -Google Brain - Ventilator Pressure Prediction](https://www.kaggle.com/competitions/ventilator-pressure-prediction/data) by building various of machine learning and deep learning model. Lastly, we perform ensemble learning to increase the overall result.
* The repository consists
  - Jupyter notebook file that contains code about data analysis of the dataset, data pre-processing, building & training of Machine Learning model (KNN, Random Forest, XGBoost, ANN, Bidirectional LSTM, Bidirectional GRU) and statistical model(ARIMA, VAR) to solve the Covid-19 ventilator control problem
  - The details explanation of the each methods used is discussed in the Jupyter notebook markdown cell.
 
## Table of content
1. Introduction <br>
  ---➤ TPE and type of data science problem for this topic <br>
2. Data analysis <br>
  ---➤ Analyse the properties of the dataset <br>
  ---➤ Analyse the relationship among (u_in, u_out, time_step) and pressure <br>
    i) Box plot<br>
    ii) Violin plot<br>
    iii) 2D graph<br>
    iv) Correlation heatmap<br>
  ---➤ Calculate the number of different R,C pairs <br>
  ---➤ Analyse the relationship among (R, C) and pressure <br>
4. Data Pre-processing <br>
  ---➤ Extracted subset of dataset from original dataset <br>
  ---➤ Scale predictor variable to range [0,1] & split data into train, test, validation <br>
5. Create & Train the model <br>
  ---➤ KNN<br>
  ---➤ Random Forest<br>
  ---➤ XGBoost<br>
  ---➤ Sequential Models for Forecasting Time Series Data<br>
    i)  ANN <br>
    ii) Bidirectional LSTM <br>
    iii) Bidirectional GRU <br>
  ---➤ Statistical Models for Forecasting Time Series Data<br>
    i)  Auto Regressive Integrated Moving Average (ARIMA) <br>
    ii) Vector Auto Regressive models (VAR) <br>
  ---➤Ensemble Learning<br>
6. Conclusion 
