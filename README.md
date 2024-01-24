# Network Intrusion Detection with PySpark and RDD Spark

This repository contains the process of detecting and preventing malicious activities on a computer network. For this project, I used PySpark for machine learning methods and RDD Spark for big data analytics on the UNSW-NB15 dataset.

## About the UNSW-NB15 Dataset

The UNSW-NB15 dataset is a publicly available dataset that contains raw network packets captured from a simulated network environment. The dataset was created by the Cyber Range Lab of the Australian Centre for Cyber Security (ACCS) at the University of New South Wales (UNSW), using the IXIA PerfectStorm tool to generate both normal and attack traffic.

The dataset consists of 2.5 million network packets, which are labeled as either normal or one of the nine attack categories: Fuzzers, Analysis, Backdoors, DoS, Exploits, Generic, Reconnaissance, Shellcode, and Worms. The dataset also provides 49 features for each packet, such as source and destination IP addresses, ports, protocols, timestamps, payload sizes, and flags.

The UNSW-NB15 dataset is a valuable resource for network intrusion detection research, as it offers insights into both genuine modern activities and synthetic, contemporary attack behaviors. The dataset also poses several challenges, such as class imbalance, feature redundancy, and high dimensionality, which require appropriate data preprocessing and analysis techniques.

## Project Overview

The main goal of this project is to apply machine learning and big data analytics techniques to the UNSW-NB15 dataset, and to gain insights into the network traffic patterns and the attack behaviors. The project consists of the following steps:

**- Loading and Preprocessing:** I loaded the UNSW-NB15 dataset from Google Drive into a PySpark session, and performed data preprocessing steps, such as handling missing values, converting string columns into usable types, and imputing missing values.

**- Clustering:** I applied the BisectingKMeans algorithm to cluster the network packets into different groups based on their features. I experimented with different cluster counts, and evaluated their effectiveness using Silhouette scores.

**- Classification:** I built a multi-classifier using the RandomForestClassifier, which is an ensemble technique that uses bagging to create multiple decision trees. I trained and tested the classifier on the network packets, and measured its accuracy and performance using various metrics and visualizations.

**- RDD Spark Analytics:** I used RDD Spark to perform big data analytics on the network packets, and to answer some real-world analytical questions. I used operations such as grouping, summing, union, and finding distinct elements to extract meaningful insights from the dataset.
