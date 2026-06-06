# ML-Based-Network-Intrusion-Detection-System-IDS-
A machine learning pipeline that detects malicious network traffic in real time using a Random Forest classifier trained on the CICIDS2017 dataset.

## Overview
This project implements a Machine Learning-based Intrusion Detection System (IDS) 
capable of identifying malicious network traffic with near-perfect accuracy. Built 
using Python and scikit-learn, the system was trained and evaluated on the 
CICIDS2017 dataset — a benchmark dataset containing real network flows labelled 
across multiple attack types including DDoS, Port Scan, and Botnet activity.

## Features
- Full data preprocessing pipeline (missing values, normalisation, label encoding)
- Random Forest classifier trained on 438,000+ network flow records
- 100% precision, recall and F1 score on 109,511 test samples
- Real-time traffic monitoring with timestamped alert logging
- Visualisations including feature importance, confusion matrix, and alert timeline

## Dataset
CICIDS2017 — Canadian Institute for Cybersecurity Intrusion Detection dataset
containing labelled network flows across 5 days of simulated traffic.

## Tech Stack
- Python 3
- scikit-learn
- pandas / numpy
- matplotlib / seaborn
- Google Colab
