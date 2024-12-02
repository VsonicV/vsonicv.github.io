---
title: Effective reinforcement learning through evolutionary surrogate-assisted prescription

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Olivier Francon
- Santiago Gonzalez
- Babak Hodjat
- Elliot Meyerson
- Risto Miikkulainen
- admin
- Hormoz Shahrzad

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2020-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-02T09:50:57.761175Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 2020 Genetic and Evolutionary Computation Conference*'
publication_short: ''

doi: 10.1145/3377930.3389842

abstract: There is now significant historical data available on decision making in
  organizations, consisting of the decision problem, what decisions were made, and
  how desirable the outcomes were. Using this data, it is possible to learn a surrogate
  model, and with that model, evolve a decision strategy that optimizes the outcomes.
  This paper introduces a general such approach, called Evolutionary Surrogate-Assisted
  Prescription, or ESP. The surrogate is, for example, a random forest or a neural
  network trained with gradient descent, and the strategy is a neural network that
  is evolved to maximize the predictions of the surrogate model. ESP is further extended
  in this paper to sequential decision-making tasks, which makes it possible to evaluate
  the framework in reinforcement learning (RL) benchmarks. Because the majority of
  evaluations are done on the surrogate, ESP is more sample efficient, has lower variance,
  and lower regret than standard RL approaches. Surprisingly, its solutions are also
  better because both the surrogate and the strategy network regularize the decision
  making behavior. ESP thus forms a promising foundation to decision optimization
  in real-world problems.

# Summary. An optional shortened abstract.
summary: ''

tags:
- decision making
- genetic algorithms
- neural networks
- reinforcement learning
- surrogate-assisted evolution

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
  url: https://doi.org/10.1145/3377930.3389842
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
