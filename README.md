# ML model on Covid-19 ventilator control problem
Author: [Ng Zheng Jue](https://github.com/xinjue37), [Ong Ming Jie](https://github.com/ethanong98), [Chiam Yu Wei](https://github.com/yuwei0410), [Lim Yi Jing](https://github.com/yijing0612), [Cheng Hung Xu](https://github.com/hxDying)

* This is a project developed in undergraduate Year 2 - Semester 1.
* This repository consists of **solving time-series data forecasting problem** on the [Kaggle -Google Brain - Ventilator Pressure Prediction](https://www.kaggle.com/competitions/ventilator-pressure-prediction/data) by building various of machine learning and deep learning model. Lastly, we perform ensemble learning to increase the overall result.
* The repository consists
  - Jupyter notebook file that contains code about data analysis of the dataset, data pre-processing, building & training of Machine Learning model (KNN, Random Forest, XGBoost, ANN, Bidirectional LSTM, Bidirectional GRU) and statistical model(ARIMA, VAR) to solve the Covid-19 ventilator control problem
  - The details explanation of the each methods used is discussed in the Jupyter notebook markdown cell.
 
## Table of content
1. Introduction
  ---➤ TPE and type of data science problem for this topic
2. Data analysis
  ---➤ Analyse the properties of the dataset
  ---➤ Analyse the relationship among (u_in, u_out, time_step) and pressure
    i) Box plot       ii) Violin plot
    iii) 2D graph         iv) Correlation heatmap
  ---➤ Calculate the number of different R,C pairs
  ---➤ Analyse the relationship among (R, C) and pressure
3. Data Pre-processing
  ---➤ Extracted subset of dataset from original dataset
  ---➤ Scale predictor variable to range [0,1] & split data into train, test, validation
4. Create & Train the model
  ---➤ KNN
  ---➤ Random Forest
  ---➤ XGBoost
  ---➤ Sequential Models for Forecasting Time Series Data
    i)  ANN
    ii) Bidirectional LSTM
    iii) Bidirectional GRU
  ---➤ Statistical Models for Forecasting Time Series Data
    i)  Auto Regressive Integrated Moving Average (ARIMA)
    ii) Vector Auto Regressive models (VAR)
  ---➤Ensemble Learning
5. Conclusion
