# Visual Manufacturing Anomaly Detection Algorithm for the Paper Industry

## Overview

This repository contains the implementation of a cutting-edge algorithm designed to detect visual manufacturing anomalies in the paper industry. Leveraging the power of autoencoder architecture, this algorithm provides robust and accurate anomaly detection capabilities. It is a critical component for ensuring high-quality production in the paper manufacturing process.

**Note:** The dataset used in this project is proprietary and cannot be shared publicly.

## Features

- Utilizes state-of-the-art autoencoder architecture for anomaly detection.
- High accuracy in identifying visual manufacturing anomalies in line.
- an optimal threshold is defined to ensure the highest precision-recall trade off


## How it Works

The algorithm works by training an autoencoder neural network on a proprietary dataset specific to the paper manufacturing process. The autoencoder is trained on normal, defect-free images, learning to reconstruct them accurately. During inference, the algorithm compares the reconstructed image with the input image. If the difference between the two surpasses a predefined threshold, the system identifies it as an anomaly, triggering necessary actions for inspection and rectification.