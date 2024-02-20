---
title: "RetainVis: Visual Analytics with Interpretable and Interactive Recurrent Neural Networks on Electronic Medical Records"
collection: publications
permalink: /publications/2019-RetainVis
excerpt: 'Electronic medical records (EMRs) are increasingly being coupled with deep learning models for predicting the future condition of a patient. In this study, we introduce RetainVis, a visual analytics tool that can be used for interpreting how each individual risk code in EMR data can contribute to the predicted outcomes such as heart failure or cataract symptoms. We provide both quantitative results of the model performance as well as qualitative use cases.'
date: 2019-01-01
venue: 'IEEE Transactions on Visualization and Computer Graphics (TVCG)'
paperurl: 'https://ieeexplore.ieee.org/document/8440842'
---

Abstract: We have recently seen many successful applications of recurrent neural networks (RNNs) on electronic medical records (EMRs), which contain histories of patients' diagnoses, medications, and other various events, in order to predict the current and future states of patients. Despite the strong performance of RNNs, it is often challenging for users to understand why the model makes a particular prediction. Such black-box nature of RNNs can impede its wide adoption in clinical practice. Furthermore, we have no established methods to interactively leverage users' domain expertise and prior knowledge as inputs for steering the model. Therefore, our design study aims to provide a visual analytics solution to increase interpretability and interactivity of RNNs via a joint effort of medical experts, artificial intelligence scientists, and visual analytics researchers. Following the iterative design process between the experts, we design, implement, and evaluate a visual analytics tool called RetainVis, which couples a newly improved, interpretable, and interactive RNN-based model called RetainEX and visualizations for users' exploration of EMR data in the context of prediction tasks. Our study shows the effective use of RetainVis for gaining insights into how individual medical codes contribute to making risk predictions, using EMRs of patients with heart failure and cataract symptoms. Our study also demonstrates how we made substantial changes to the state-of-the-art RNN model called RETAIN in order to make use of temporal information and increase interactivity. This study will provide a useful guideline for researchers that aim to design an interpretable and interactive visual analytics tool for RNNs.

[Alternative download link for paper (arxiv)](https://arxiv.org/abs/1805.10724)

[Code and models used for the paper](https://github.com/minjechoi/RetainVis)