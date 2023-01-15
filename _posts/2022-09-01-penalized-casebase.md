---
layout: post
title: Penalized Casebase in Survival Analysis
subtitle: Each post also has a subtitle
gh-repo: trevorkwan
tags: [survival analysis] []
comments: false
---

A quantity of interest in clinical studies is the absolute risk of an event given a patient’s covariate profile. In order for the Cox proportional hazard method to recover these absolute risk curves, the baseline hazard needs to be estimated separately, resulting in stepwise estimates in absolute risk that make the curves difficult to interpret. Casebase is an approach that transforms the data into a logistic regression, allowing for survival estimates that vary smoothly over time. We simulate data and compare the prediction performance of penalized Casebase methods with penalized and unpenalized Cox methods. Casebase methods perform better in measures of concordance and time-dependent brier scores.

My final code script can be found [here](https://github.com/trevorkwan/Penalized-Casebase-in-Survival-Analysis-MSc-Project-/blob/main/R/final_code_casebase_sim_study.Rmd).

My final project report can be found [here](https://github.com/trevorkwan/Penalized-Casebase-in-Survival-Analysis-MSc-Project-/blob/main/reports/Final_MSc_Final_Project_Report_Trevor.pdf).

My final presentation slides can be found [here](https://github.com/trevorkwan/Penalized-Casebase-in-Survival-Analysis-MSc-Project-/blob/main/presentations/Final_MSc_Final_Presentation_Trevor.pdf)
