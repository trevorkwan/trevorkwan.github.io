---
layout: post
title: Classifying Non-Synoptic Cancer Reports with BERT NLP Models
subtitle: UBC DSI Project
gh-repo: trevorkwan
thumbnail-img: /assets/img/non_synoptic.png
tags: [question answering, text classification, BERT]
comments: false
---

In this project, I develop a Machine Learning pipeline that automates free-text cancer report classification with near-human-level accuracy at 90% using BERT NLP for question answering and text classification. In step one, I trained BERT question answering models to extract relevant text from unstructured non-synoptic reports, evaluated these models on their predictions, and inferred their performance with metrics f1-score, Precision, and Recall. In step two, I trained BERT text classification models to take extracted relevant text from question answering models and classify them into cancer fields of interest. Classifiers were evaluated on accuracy within and across fields of interest.

My work can be found [here](https://github.com/trevorkwan/Breast-Cancer-Non-Synoptic-Pathology-Reports-BERT-Classification).
