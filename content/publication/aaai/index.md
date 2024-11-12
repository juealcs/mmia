---
title: 'CorBin-FL: A Differentially Private Federated Learning Mechanism using Common Randomness'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Hojat Allah Salehi
  - admin
  - S. Sandeep Pradhan
  - M. Hadi Amini
  - Farhad Shirani

date: '2024-09-20T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2409.13133'

publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: arXiv, 2024.
publication_short: arXiv, 2024.

abstract: Federated learning (FL) has emerged as a promising framework for distributed machine learning. It enables collaborative learning among multiple clients, utilizing distributed data and computing resources. However, FL faces challenges in balancing privacy guarantees, communication efficiency, and overall model accuracy. In this work, we introduce CorBin-FL, a privacy mechanism that uses correlated binary stochastic quantization to achieve differential privacy while maintaining overall model accuracy. The approach uses secure multi-party computation techniques to enable clients to perform correlated quantization of their local model updates without compromising individual privacy. We provide theoretical analysis showing that CorBin-FL achieves parameter-level local differential privacy (PLDP), and that it asymptotically optimizes the privacy-utility trade-off between the mean square error utility measure and the PLDP privacy measure. We further propose AugCorBin-FL, an extension that, in addition to PLDP, achieves user-level and sample-level central differential privacy guarantees. For both mechanisms, we derive bounds on privacy parameters and mean squared error performance measures. Extensive experiments on MNIST and CIFAR10 datasets demonstrate that our mechanisms outperform existing differentially private FL mechanisms, including Gaussian and Laplacian mechanisms, in terms of model accuracy under equal PLDP privacy budgets.

# Summary. An optional shortened abstract.
summary: CorBin-FL introduces a privacy mechanism that uses correlated binary stochastic quantization to achieve differential privacy in federated learning while optimizing the trade-off between model accuracy and privacy.

tags:
  - Machine Learning
  - Privacy and Security Issues in Federated Learning
  - Deep Learning

featured: true

url_pdf: 'https://arxiv.org/pdf/2409.13133'

# url_code: 'https://figshare.com/articles/dataset/An_Empirical_Study_of_Deep_Learning_Models_for_Vulnerability_Detection/20791240'
# url_dataset: 'https://figshare.com/articles/dataset/An_Empirical_Study_of_Deep_Learning_Models_for_Vulnerability_Detection/20791240'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://link.springer.com/chapter/10.1007/978-3-031-27409-1_15'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Privacy in Distributed Machine Learning'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
# - paper_reviews

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
