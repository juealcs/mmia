---
title: 'JaiLIP: Jailbreaking Vision-Language Models via Loss Guided Image Perturbation'

authors:
  - admin
  - M. Hadi Amini

date: '2025-12-03T00:00:00Z'
doi: 'https://doi.org/10.1109/ICMLA66185.2025.00217'

publication_types: ['paper-conference']

publication: 2025 IEEE International Conference on Machine Learning and Applications (ICMLA)
publication_short: IEEE ICMLA

abstract: |
  Vision-Language Models (VLMs) have demonstrated remarkable capabilities in multimodal reasoning and generation. However, their widespread adoption has also introduced significant safety and security concerns, particularly regarding jailbreak attacks that bypass alignment mechanisms. We propose JaiLIP (Jailbreaking with Loss-guided Image Perturbation), a novel image-space jailbreak attack that optimizes a joint objective combining the mean squared error (MSE) between clean and adversarial images with the model's harmful-output loss. This optimization produces highly effective yet visually imperceptible adversarial examples capable of inducing unsafe model behavior. We evaluate JaiLIP using Perspective API and Detoxify toxicity metrics across multiple Vision-Language Models. Experimental results show that JaiLIP consistently outperforms existing image-based jailbreak attacks while maintaining minimal visual distortion. Furthermore, we demonstrate the practicality of the attack in intelligent transportation scenarios, highlighting security vulnerabilities of multimodal AI systems and motivating the need for stronger defense mechanisms.

summary: >
  JaiLIP introduces a loss-guided optimization framework for jailbreaking Vision-Language Models through imperceptible image perturbations. By jointly optimizing image fidelity and harmful-response objectives, the method generates highly effective adversarial images that outperform prior image-based jailbreak attacks. Extensive experiments using Perspective API and Detoxify demonstrate increased attack effectiveness while preserving visual quality, and evaluations in intelligent transportation applications highlight real-world security risks for multimodal AI systems.
  
  
tags:
  - Vision-Language Models
  - AI Security
  - Jailbreak Attacks
  - Adversarial Machine Learning
  - Multimodal AI

featured: true

url_pdf: 'https://ieeexplore.ieee.org/document/11471319'

image:
  caption: 'JaiLIP: Jailbreaking Vision-Language Models via Loss Guided Image Perturbation'
  focal_point: Smart
  preview_only: false
---
