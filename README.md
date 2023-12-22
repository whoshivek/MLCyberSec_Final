# AdTracking Fraud Detection
---
Submission by: Sukriti Macker (sm11017), Shivek Aggarwal (sa7495), Prajna Nayak (), Sahil Harwani (sh7253)
---
## Problem Statement
- The project's primary focus revolves around addressing the pervasive issue of click fraud within the realm of online advertising, particularly in China's expansive mobile market.
- The project addresses the critical need to safeguard advertising investments, enhance the accuracy of analytics, and build trust in online advertising by combating click fraud within China's expansive mobile market and beyond.

## Overview
The proposed approach aims to tackle the challenge of click fraud detection in online advertising, focusing on a binary classification problem: distinguishing between fraudulent and non-fraudulent user clicks.

## Approach
The project’s foundation lies in the exploration of dataset pertaining to the AdTracking Fraud Detection. The dataset, though extensive, was strategically sampled for analysis using Python. The specific task entailed predicting user app downloads subsequent to ad clicks, framed as a binary classification problem with evaluation via the ROC-AUC metric. Throughout this study, a comprehensive analysis of both XGBoost and LightGBM models was conducted on a dataset comprising various features related to user behavior, device information, and ad interaction patterns. The goal was to identify fraudulent activities among clicks and distinguish them from legitimate user engagements. In conclusion, both XGBoost and LightGBM demonstrated promising capabilities in ad click fraud detection. While LightGBM exhibited superior efficiency and scalability, XGBoost provided better interpretability. The choice between the two models should be made considering the specific requirements of the ad fraud detection system, such as the scale of data, interpretability needs, and computational efficiency.
