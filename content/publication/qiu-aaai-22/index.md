---
title: Detecting Misclassification Errors in Neural Networks with a Gaussian Process
  Model

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Risto Miikkulainen

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-06-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-11-30T14:37:06.857830Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the AAAI Conference on Artificial Intelligence (AAAI 2022)*, oral presentation (top ~4.5% of all submissions)'
publication_short: ''

doi: 10.1609/aaai.v36i7.20773

abstract: 'As neural network classifiers are deployed in real-world applications, it is crucial that their failures can be detected reliably. One practical solution is to assign confidence scores to each prediction, then use these scores to filter out possible misclassifications. However, existing confidence metrics are not yet sufficiently reliable for this role. This paper presents a new framework that produces a quantitative metric for detecting misclassification errors. This framework, RED, builds an error detector on top of the base classifier and estimates uncertainty of the detection scores using Gaussian Processes. Experimental comparisons with other error detection methods on 125 UCI datasets demonstrate that this approach is effective. Further implementations on two probabilistic base classifiers and two large deep learning architecture in vision tasks further confirm that the method is robust and scalable. Third, an empirical analysis of RED with out-of-distribution and adversarial samples shows that the method can be used not only to detect errors but also to understand where they come from. RED can thereby be used to improve trustworthiness of neural network classifiers more broadly in the future.'

# Summary. An optional shortened abstract.
summary: ''

tags: [AAAI 2022 Oral]

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: 'https://arxiv.org/pdf/2010.02065'
url_code: 'https://github.com/cognizant-ai-labs/red-paper'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# Publication image
# Add an image named `featured.jpg/png` to your page's folder then add a caption below.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects: ['internal-project']` links to `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
links:
- name: URL
  url: https://ojs.aaai.org/index.php/AAAI/article/view/20773
---

