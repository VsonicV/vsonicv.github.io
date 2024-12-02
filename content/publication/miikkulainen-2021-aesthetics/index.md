---
title: Evaluating medical aesthetics treatments through evolved age-estimation models

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Risto Miikkulainen
- Elliot Meyerson
- Xin Qiu
- Ujjayant Sinha
- Raghav Kumar
- Karen Hofmann
- Yiyang Matt Yan
- Michael Ye
- Jingyuan Yang
- Damon Caiazza
- Stephanie Manson Brown

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2021-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-02T09:50:57.736235Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the Genetic and Evolutionary Computation Conference*'
publication_short: ''

doi: 10.1145/3449639.3459378

abstract: "Estimating a person's age from a facial image is a challenging problem
  with clinical applications. Several medical aesthetics treatments have been developed
  that alter the skin texture and other facial features, with the goal of potentially
  improving patient's appearance and perceived age. In this paper, this effect was
  evaluated using evolutionary neural networks with uncertainty estimation. First,
  a realistic dataset was obtained from clinical studies that makes it possible to
  estimate age more reliably than e.g. datasets of celebrity images. Second, a neuroevolution
  approach was developed that customizes the architecture, learning, and data augmentation
  hyperparameters and the loss function to this task. Using state-of-the-art computer
  vision architectures as a starting point, evolution improved their original accuracy
  significantly, eventually outperforming the best human optimizations in this task.
  Third, the reliability of the age predictions was estimated using RIO, a Gaussian-Process-based
  uncertainty model. Evaluation on a real-world Botox treatment dataset shows that
  the treatment has a quantifiable result: The patients' estimated age is reduced
  significantly compared to placebo treatments. The study thus shows how AI can be
  harnessed in a new role: To provide an objective quantitative measure of a subjective
  perception, in this case the proposed effectiveness of medical aesthetics treatments."

# Summary. An optional shortened abstract.
summary: ''

tags:
- uncertainty estimation
- real-world applications
- neural architecture search
- medical aesthetics

# Display this page in a list of Featured pages?
featured: false

# Links
url_pdf: ''
url_code: ''
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
  url: https://doi.org/10.1145/3449639.3459378
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
