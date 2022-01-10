# Anomaly-Detection-in-IoT-23

A comparative analysis of ML and DL models on the IoT-23 dataset for anomaly detection.

## Background

Anomaly detection is very similar to outlier analysis. It is a step in data mining that identifies data points, events, and observations that deviate from a dataset's normal behavior. Anomalous data can indicate critical incidents, such as technical glitches, etc. The complex networks behind IoT and its increasing applicability in solving complex and everyday challenges make it highly prone to security failure and its enormous ramifications. Hence, anomaly detection is of utmost importance in the Internet of Things. 

## Literature Review 

The use of ML for IoT Detection is still relatively new. Although some frameworks have been developed, most research work focuses on implementation and testing. However, the scope of using ML and DL is immense in IoT since the devices are **less complex than traditional systems**, making them **more predictable**, and **data for analysis is readily available**. 

**1.** There are two significant ways of implementing ML algorithms in IoT networks:

- **Network-based**: Using metadata from the IoT network
- **Host-based**: Using the information present on the device

  This project will be focused on a **network-based implementation of ML** while also performing classification using **Convolutional Neural Networks (CNN)** and **Multi-Layer       Perceptrons (MLP)**.

**2.** It was found that the best four metrics for testing the models built are the actual positives rate (TPRate), the precision, the accuracy, and the time taken to build the model.

**3.** By doing some meta-analysis of this literature review, it can be seen that the **use of ML on IoT networks is a very recent development**, with all the papers being less than 3-years old. It should also be noted that even **in comparison to significantly more complex algorithms**, such as neural networks (Artificial Neural Networks), most of the studies found the best results using algorithms such as **Naıve Bayes** and **Random Forest**. The findings of this report also corroborated these results. 

## Dataset

The data set used in this project is **IoT-23**.

The Avast AIC laboratory creates this dataset. The dataset consists of **20 malware captures** and  **3 captures for benign anomalies**. The data set contains a total of **325,307,990 captures**, of which **294,449,255 are malicious**

![alt text](https://github.com/sen-28/Vision-Transformers/blob/main/vision_images/IoT-23.png)
.
Two versions of this dataset have been made available on their official site by the creators - the complete version (which contains **both pcap files** and **conn.log.labeled files**), and a lighter version (which only contains the conn.log.labeled files). 

**The pcap files are the original network capture files while the conn.log.labeled files have been created by running a network analyzer on them. **

The **lighter version** was chosen since working with .pcap files proved unnecessary difficult for this project as **they created by the network capture program Wireshark** and **can only be opened using it**. 





