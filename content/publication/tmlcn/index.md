---
title: 'BART-FL: A Backdoor Attack-Resilient Federated Aggregation Technique for Cross-Silo Applications'

authors:
  - admin
  - M. Hadi Amini

date: '2025-09-18T00:00:00Z'
doi: 'https://doi.org/10.1109/TMLCN.2025.3611398'

publication_types: ['article-journal']

publication: IEEE Transactions on Machine Learning in Communications and Networking
publication_short: i3ce, 2024

abstract: |
  Federated Learning lends itself as a promising paradigm for enabling distributed learning in autonomous vehicle applications, ensuring data privacy while enhancing predictive model performance through collaborative training on edge client vehicles. However, it remains vulnerable to various categories of cyber-attacks, necessitating more robust security measures to effectively mitigate potential threats. Poisoning and inference attacks are commonly initiated within the federated learning environment to compromise system security. Secure aggregation can limit the disclosure of sensitive information from both outsider and insider attackers. This study conducts an empirical analysis on the transportation image dataset (e.g., LISA traffic light) using various secure aggregation techniques and multiparty computation in the presence of diverse cyber-attacks. Multiparty computation serves as a state-of-the-art security mechanism, providing privacy-preserving aggregation of local model updates from autonomous vehicles through multiple security protocols. The findings demonstrate how adversaries can mislead autonomous vehicle models, causing traffic light misclassification and potential hazards. This study explores the resilience of different secure federated learning aggregation and multiparty computation methods in safeguarding autonomous vehicle applications against cyber threats during both training and inference phases.

summary: This paper introduces BART-FL (Backdoor Attack Resilient Technique for Federated Learning), a lightweight defense mechanism designed to detect and filter malicious client updates in federated learning. By combining Principal Component Analysis (PCA), cosine similarity, and K-means clustering with a multi-metric statistical voting system, BART-FL effectively identifies adversarial clients before model aggregation. Experiments on LISA traffic light, CIFAR-10, and CIFAR-100 datasets demonstrate that BART-FL enhances model robustness against backdoor attacks while maintaining high accuracy and computational efficiency.

tags:
  - Privacy and security
  - Federated Learning
  - Machine Learning

featured: true

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11172307'

image:
  caption: 'BART-FL: A Backdoor Attack-Resilient Federated Aggregation Technique for Cross-Silo Applications'
  focal_point: ''
  preview_only: false
---
