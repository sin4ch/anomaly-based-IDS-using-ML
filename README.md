# Anomaly-based Intrusion Detection System using kNN, Decision Tree and Random Forest

## Introduction
This project aims to develop an anomaly-based intrusion detection system (AIDS) using machine learning (ML) models. Anomaly-based IDSs detect intrusions by comparing the network traffic with a normal baseline and flagging any deviations as potential attacks. Machine learning techniques can help to learn the normal behavior of the network and identify unknown or zero-day attacks.

## Motivation
Network security is a critical issue in the modern world, as cyberattacks can cause severe damage to individuals, organizations, and governments. Traditional signature-based IDSs rely on predefined rules or patterns to detect known attacks, but they are ineffective against novel or sophisticated attacks. Anomaly-based IDSs can overcome this limitation by using machine learning models to learn the normal network behavior and detect any anomalies. However, anomaly-based IDSs also face challenges such as high false alarm rate, feature selection, and scalability.

## Dataset
The CICIDS2017 dataset is a realistic and up-to-date dataset of network traffic analysis and intrusion detection systems, covering common attacks, background traffic, and features1. It contains benign and the most up-to-date common attacks, which resembles the true real-world data (PCAPs). It also includes the results of the network traffic analysis using CICFlowMeter with labeled flows based on the time stamp, source, and destination IPs, source and destination ports, protocols and attack (CSV files)1.

## Methodology
The methodology of this project consists of the following steps:

## Data preprocessing: The data is cleaned, normalized, and encoded to make it suitable for machine learning models.
Feature selection: The features are ranked and selected based on their relevance and importance for anomaly detection using various techniques such as correlation analysis, information gain, and chi-square test.
Model training: The selected features are used to train different machine learning models such as decision tree, random forest, and k-nearest neighbors
Model evaluation: The trained models are evaluated on the test dataset using various metrics such as accuracy, precision, recall, f1-score, and confusion matrix.
Model comparison: The performance of the different models is compared and analyzed to find the best model for anomaly detection.
