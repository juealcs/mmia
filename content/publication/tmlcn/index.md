---
title: "BART-FL: A Backdoor Attack-Resilient Federated Aggregation Technique for Cross-Silo Applications"

authors:
  - admin
  - M. Hadi Amini

date: "2025-09-18T00:00:00Z"

doi: "https://doi.org/10.1109/TMLCN.2025.3611398"

publication_types:
  - article-journal

publication: "IEEE Transactions on Machine Learning in Communications and Networking"
publication_short: "IEEE TMLCN"

abstract: |
  Federated Learning (FL) is a decentralized learning paradigm that enables collaborative model training while preserving data privacy, making it particularly suitable for cross-silo applications such as healthcare, finance, and transportation. Despite its advantages, FL remains highly vulnerable to backdoor attacks, where malicious clients inject poisoned model updates to manipulate the global model. Existing outlier detection techniques often struggle to accurately distinguish malicious updates from benign ones, limiting their effectiveness in adversarial settings. To address this challenge, we propose BART-FL (Backdoor Attack Resilient Technique for Federated Learning), a lightweight defense mechanism that filters malicious client updates before model aggregation. BART-FL combines Principal Component Analysis (PCA) for dimensionality reduction, cosine similarity for measuring pairwise distances between client updates, and K-means clustering for identifying suspicious clients. Furthermore, it introduces a multi-metric statistical voting strategy based on point-level mean, Median Absolute Deviation (MAD), and cluster-level mean to reliably identify the benign cluster. Experimental evaluations on the LISA traffic light, CIFAR-10, and CIFAR-100 datasets demonstrate that BART-FL effectively mitigates backdoor attacks while maintaining high model accuracy and computational efficiency. Comparative analyses against existing defense techniques further highlight BART-FL as a scalable and resilient solution for secure cross-silo federated learning.

summary: |
  BART-FL is a lightweight defense framework for secure federated learning that detects and filters malicious client updates before aggregation. By integrating PCA, cosine similarity, K-means clustering, and a multi-metric statistical voting mechanism, BART-FL effectively defends against backdoor attacks while preserving model accuracy and computational efficiency across multiple benchmark datasets.

tags:
  - Federated Learning
  - Backdoor Attacks
  - AI Security
  - Privacy-Preserving Machine Learning
  - Distributed Machine Learning

featured: true

url_pdf: "https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=11172307"
url_code: ""
url_dataset: ""
url_project: ""

image:
  caption: "BART-FL framework for resilient federated learning against backdoor attacks."
  focal_point: "Center"
  preview_only: false
---
