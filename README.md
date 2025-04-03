# Malicious Traffic Classification in MQTT-IoT Networks

## Overview  
With the rapid growth of IoT devices, ensuring robust security measures is essential to defend against malicious network traffic. 
This repository contains Jupyter Notebooks implementing **statistical moments difference thresholding (SMDT)**,
a feature selection technique that enhances IoT network security by identifying key features for **malicious traffic classification**. 

The study evaluates feature selection effectiveness using the **MQTTset dataset** ([available on Kaggle](https://www.kaggle.com/datasets/cnrieiit/mqttset))
and applies **binary and multiclass classification** using seven machine learning algorithms.
The goal is to **reduce feature dimensionality** while maintaining **high detection accuracy**, making the approach suitable for resource-constrained IoT environments.

## Contents  
- `Binary_case.ipynb` – Notebook for classifying traffic as **legitimate (0) vs. malicious (1)**.  
- `Multiclass_case.ipynb` – Notebook for categorizing traffic into multiple attack types (classes).
-  `README.md` – This file.  

## Key Features  
- **Feature selection using statistical moments difference thresholding**  
- **Evaluation using multiple ML classifiers**  
- **Optimized for computational efficiency in IoT security applications**  

## Dataset  
The dataset used in this study is **MQTTset**, created and discussed in the following research paper:  

📄 **Vaccari, I.; Chiola, G.; Aiello, M.; Mongelli, M.; Cambiaso, E.**  
*"MQTTset, a New Dataset for Machine Learning Techniques on MQTT."*  
**Sensors 2020, 20, 6578** ([DOI: 10.3390/s20226578](https://doi.org/10.3390/s20226578))  

🔗 **Access the dataset on Kaggle:** [MQTTset Dataset](https://www.kaggle.com/datasets/cnrieiit/mqttset)  
## Keywords  
Anomaly detection • Feature selection • Intrusion detection system • Machine learning • MQTT • Traffic classification  
