---
title: 'A Secure Object Detection Technique for Intelligent Transportation Systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - M. Hadi Amini
# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-08-08T00:00:00Z'
doi: 'https://doi.org/10.1109/OJITS.2024.3440876'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE OJ-ITS, August, 2024
publication_short: IEEE OJ-ITS, August, 2024

abstract: Federated Learning is a decentralized machine learning technique that creates a global model by aggregating local models from multiple edge devices without a need to access the local data. However, due to the distributed nature of federated learning, there is a larger attack surface, making cyber-attack detection and defense challenging. Although prior works developed various defense strategies to address security issues in federated learning settings, most approaches fail to mitigate cyber-attacks due to the diverse characteristics of the attack, edge devices, and data distribution. To address this issue, this paper develops a hybrid privacy-preserving algorithm to safeguard federated learning methods against malicious attacks in Intelligent Transportation Systems, considering object detection as a downstream machine learning task. This algorithm involves the edge devices (e.g., autonomous vehicles) and road side units to collaboratively train their model while maintaining the privacy of their respective data. Furthermore, this hybrid algorithm provides robust security against data poisoning-based model replacement and inference attacks throughout the training phase. We evaluated our model using the CIFAR10 and LISA traffic light dataset, demonstrating its ability to mitigate malicious attacks with minimal impact on the performance of main tasks.
# Summary. An optional shortened abstract.
summary: A hybrid privacy-preserving algorithm combining Pre-Aggregation Similarity Measurement (PA-SM) and Differential Privacy (DP) enhances the security and resilience of Federated Learning (FL) in Intelligent Transportation Systems (ITS) by defending against adversarial attacks while maintaining model performance.
tags:
  - Privacy and security 
  - Federated Learning
  - Machine Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10630660'
# url_code: 'https://figshare.com/s/0ffda320dcb96c249ef2'
# url_dataset: 'https://figshare.com/s/0ffda320dcb96c249ef2'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://www.sciencedirect.com/science/article/pii/S2590005623000383'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Secured Object Detection in ITS'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
# - traffic_model

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
