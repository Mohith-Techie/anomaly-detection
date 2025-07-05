# anomaly-detection
A machine learning project to detect abnormal server performance using Gaussian-based anomaly detection on real-world throughput and latency data.
# Anomaly Detection for Server Performance

## Project Overview
Detecting abnormal server behavior is crucial for maintaining reliable and efficient IT infrastructure. This project implements a machine learning solution to automatically identify unusual patterns in server performance data, focusing on throughput and latency metrics. The approach leverages Gaussian-based anomaly detection to flag potential issues before they escalate.

## Features
- Unsupervised anomaly detection using statistical modeling
- Parameter estimation for Gaussian distributions
- Automated threshold selection with F1-score optimization
- Visualization of normal and anomalous data points
- Scalable to both low- and high-dimensional datasets

## Dataset
- **Training Data:** Server performance logs with features such as throughput (mb/s) and latency (ms)
- **Validation Data:** Labeled examples for threshold tuning and evaluation
- **High-dimensional Extension:** Includes additional server metrics for more robust detection

## Approach
1. **Data Exploration:** Visualize and understand server performance metrics
2. **Modeling:** Estimate mean and variance for each feature to fit a Gaussian model
3. **Probability Scoring:** Compute the likelihood of each data point under the model
4. **Threshold Selection:** Use validation data to find the optimal cutoff for anomaly detection
5. **Evaluation:** Assess performance using precision, recall, and F1-score
6. **Visualization:** Highlight detected anomalies for interpretability

## Results
- Achieved high accuracy in identifying abnormal server behavior
- Detected both subtle and extreme anomalies in real and synthetic datasets
- Visualizations provide clear insights into model decisions and flagged outliers

## How to Run
1. Clone this repository to your local machine
2. Open `Anomaly_Detection.ipynb` in Jupyter Notebook
3. Run all cells sequentially to reproduce the analysis and results