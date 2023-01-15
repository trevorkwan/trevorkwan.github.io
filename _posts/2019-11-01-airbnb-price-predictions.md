---
layout: post
title: Airbnb Price Predictions
subtitle: MDS Course Project
gh-repo: trevorkwan
tags: [linear regression, feature selection]
comments: false
---

In this project, we build a predictive model to help new AirBnB hosts set the nightly price of their Vancouver AirBnB. Our predictive model predicts the market price of an AirBnb given the property, host, and booking characteristics which we believe gives the optimal price for both the host and AirBnB guests. 

At this stage, we have trained a variety of machine learning models based on property-, host- and book-related characteristics of existing Vancouver AirBnBs. Examples of characteristics include property type, neighborhood, the number of people who can be accommodated, the ability to instant book the property, the booking's cancellation policy and the responsiveness of the host. 

Surprisingly, our linear regression predictor exceeded the performance of more complex machine learning models that were evaluated (e.g., random forest regressor). This model, however, tends to consistently overestimate the price of AirBnB's below \$200/night and underestimate the price of AirBnB's above \$300/night. Further work should involve feature engineering to model interactions between features (e.g., neighborhood and property type) as well as fitting more complex linear models (e.g., that better model pricing behaviour above $300/night). 

My work can be found [here](https://github.com/trevorkwan/Airbnb-Price-Prediction-Project-DSCI-522).
