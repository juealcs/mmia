---
title: 'QuanCrypt-FL: Quantized Homomorphic Encryption with Pruning for Secure Federated Learning'

authors:
  - admin
  - M. Hadi Amini

date: '2025-10-08T00:00:00Z'
doi: 'https://doi.org/10.1109/TAI.2025.3612906'

publication_types: ['article-journal']

publication: IEEE Transactions on Artificial Intelligence
publication_short: IEEE TAI

abstract: |
  Federated learning has emerged as a leading approach for decentralized machine learning, enabling multiple clients to collaboratively train a shared model without exchanging private data. While federated learning enhances data privacy, it remains vulnerable to inference attacks, such as gradient inversion and membership inference, during both the training and inference phases. We propose QuanCrypt-FL, a communication-efficient federated learning framework that integrates fully homomorphic encryption (FHE), low-bit quantization, dynamic pruning, and a novel mean-based clipping strategy to provide strong privacy protection while substantially reducing computational overhead. By combining these techniques, QuanCrypt-FL defends against inference attacks, minimizes encryption and communication costs, and preserves model accuracy. Extensive experiments on MNIST, HAM10000, CIFAR-10, and CIFAR-100 demonstrate that QuanCrypt-FL consistently matches the accuracy of Vanilla-FL while outperforming existing privacy-preserving approaches, achieving up to 9× faster encryption, 16× faster decryption, 3× faster training, and 1.5× faster inference.

summary: >
  QuanCrypt-FL introduces a secure and efficient federated learning framework that combines fully homomorphic encryption, low-bit quantization, dynamic pruning, and mean-based clipping to defend against gradient inversion and membership inference attacks. The proposed approach significantly reduces communication and computational overhead while maintaining model accuracy. Extensive evaluations on MNIST, HAM10000, CIFAR-10, and CIFAR-100 demonstrate substantial improvements in efficiency, including up to 9× faster encryption, 16× faster decryption, 3× faster training, and 1.5× faster inference compared with existing secure federated learning methods.

tags:
  - Federated Learning
  - Privacy-Preserving Machine Learning
  - AI Security
  - Trustworthy AI

featured: true

url_pdf: 'https://ieeexplore.ieee.org/document/11196960'

image:
  caption: 'QuanCrypt-FL: Quantized Homomorphic Encryption with Pruning for Secure Federated Learning'
  focal_point: Smart
  preview_only: false
---
