# Comparison and evaluation of machine learning models (kNN, Decision Tree, Random Forest, XGBoost) for analysis of the CICIDS2017 Dataset for an anomaly-based IDS

## Introduction
Network security is a critical issue in the modern world, as cyberattacks can cause severe damage to individuals, organizations, and governments. More than ever before, improving malware detection mechanisms have grown to be more and more essential in the new world of big data. To address these issues, there are two means of detecting malware. Traditional signature-based IDSs rely on predefined rules or patterns to detect known attacks, but they are ineffective against novel or sophisticated attacks. 

![IDS classification](https://github.com/sin4ch/anomaly-based-IDS-using-ML/blob/main/Types-of-Intrusion-Detection-Techniques.png)

Anomaly-based IDSs can overcome this limitation by using machine learning models to learn the normal network behavior and detect any anomalies. Anomaly-based IDSs detect intrusions by comparing the network traffic with a normal baseline and flagging any deviations as potential attacks. Machine learning techniques can help to learn the normal behavior of the network and identify unknown or zero-day attacks.

This project aims to make a comparison anomaly-based intrusion detection system (AIDS) using supervised machine learning (ML) models such as the k-Nearest Neighbour, Decision Tree, Random Forest and XGBoost. It also evaluates their effectiveness by deriving their `accuracy`, `f1`, `precision` and `recall` scores.

## Dataset
The CICIDS2017 dataset is a realistic and up-to-date dataset of network traffic analysis and intrusion detection systems, covering common attacks, background traffic, and features. It contains benign and the most up-to-date common attacks, which resembles the true real-world data (PCAPs).

The composition, or _features_, of the datatset is shown in the diagram below:  

![CICIDS2017 composition](https://github.com/sin4ch/anomaly-based-IDS-using-ML/blob/main/Distribution-of-labels-in-the-CICIDS2017-dataset.png)

It also includes the results of the network traffic analysis using CICFlowMeter with labeled flows based on the time stamp, source, and destination IPs, source and destination ports, protocols and attack (CSV files).



## Results

_Training and Test Accuracies_:  

![accuracy scores; training and test times](https://github.com/sin4ch/anomaly-based-IDS-using-ML/blob/main/Screenshot%202024-04-09%20114124.png)

## `F1`, `Recall` & `Precision` scores of:
- XGBoost:

![XGBoost Recall, Precision and F1 scores](https://github.com/sin4ch/anomaly-based-IDS-using-ML/blob/main/XGBoost.png)
- KNN

![KNN Recall, Precision and F1 scores](https://github.com/sin4ch/anomaly-based-IDS-using-ML/blob/main/KNN.png)
- Random Forest (RF)

![RF Recall, Precision and F1 scores](https://github.com/sin4ch/anomaly-based-IDS-using-ML/blob/main/RandomForest.png)
- Decision Tree (DT)
  
![DT Recall, Precision and F1 scores](https://github.com/sin4ch/anomaly-based-IDS-using-ML/blob/main/Decision_Tree.png)




