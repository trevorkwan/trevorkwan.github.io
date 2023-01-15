---
layout: post
title: Stock trading dashboard using the DEMA strategy.
subtitle: MSc Course Project
gh-repo: trevorkwan
thumbnail-img: /assets/img/stock_trading.png
tags: [DEMA, faang]
comments: false
---

The DEMA crossover trading strategy executes a buy when the shorter term DEMA is greater than the longer term DEMA (crossing upwards), and executes a sell when the shorter term DEMA is less than the longer term DEMA (crossing downwards).

The dashboard plots the adjusted closing price of Faang stock and two double exponential moving averages (DEMA) within a specified time frame. The app simulates the DEMA crossover trading strategy, calculating:

1. Aggregate Profit/Loss
This is the cumulative profit or loss within the specified time frame if you had bought and sold exactly 1 share at each buy and sell point starting at $0.
2. Aggregate Rate of Return
This is the sum of all rate of returns if you had bought and sold at each specified buy and sell point.
Rate of Return = (sell price - buy price) / buy price

When choosing DEMA input values, the short term DEMA value must always be less than the long term DEMA value.

## Example
Shown below is what the dashboard would look like when you run the source code:

![alt text](https://raw.githubusercontent.com/trevorkwan/trevorkwan.github.io/master/assets/img/dema_faang_pic.png)

My work can be found [here](https://github.com/trevorkwan/Stock-Trading-Strategy-Project-STAT-545).
