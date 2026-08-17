---
title: 'Jailbreaking Large Vision-Language Models in Intelligent Transportation Systems'

authors:
  - Badhan Chandra Das
  - Md Tasnim Jawad
  - admin
  - M. Hadi Amini
  - Yanzhao Wu

date: '2025-12-03T00:00:00Z'
doi: 'https://doi.org/10.1109/ICMLA66185.2025.00217'

publication_types: ['paper-conference']

publication: 2025 IEEE International Conference on Machine Learning and Applications (ICMLA)
publication_short: IEEE ICMLA

abstract: |
  Large Vision-Language Models (LVLMs) have demonstrated remarkable capabilities in multimodal reasoning and are increasingly deployed in real-world applications, including Intelligent Transportation Systems (ITS). However, these models remain highly vulnerable to jailbreak attacks that circumvent built-in safety mechanisms. This paper presents a systematic security analysis of LVLMs deployed in ITS under carefully crafted jailbreak attacks. We first construct a transportation-specific benchmark of harmful multimodal queries based on OpenAI's prohibited content categories. We then propose a novel jailbreak attack that combines image typography manipulation with multi-turn prompting to conceal malicious intent while steering the model toward unsafe responses. To mitigate these attacks, we introduce a multi-layered response filtering defense that integrates rule-based filtering with a zero-shot classifier. Extensive experiments on both open-source and commercial LVLMs demonstrate the effectiveness of the proposed attack and defense. Attack success is evaluated using GPT-4-based toxicity assessment together with manual verification, and comparisons with existing jailbreak techniques highlight the significant security risks posed by image typography manipulation and multi-turn prompting in LVLM-enabled intelligent transportation applications.

summary: >
  This paper provides one of the first comprehensive security evaluations of Large Vision-Language Models in Intelligent Transportation Systems. We introduce a transportation-specific jailbreak benchmark, propose a novel attack combining image typography manipulation with multi-turn prompting, and develop a multi-layered defense integrating rule-based filtering and zero-shot classification. Extensive experiments on both open-source and proprietary LVLMs demonstrate the effectiveness of the proposed methods and highlight critical security challenges for deploying multimodal AI in safety-critical transportation systems.

tags:
  - Vision-Language Models
  - Intelligent Transportation Systems
  - AI Security
  - Jailbreak Attacks
  - Multimodal AI
  - Adversarial Machine Learning

featured: false

url_pdf: 'https://ieeexplore.ieee.org/document/11471319'

image:
  caption: 'Jailbreaking Large Vision-Language Models in Intelligent Transportation Systems'
  focal_point: Smart
  preview_only: false
  
---
