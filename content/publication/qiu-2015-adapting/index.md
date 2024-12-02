---
title: A New Framework for Self-adapting Control Parameters in Multi-objective Optimization

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Xin Qiu
- Weinan Xu
- Jian-Xin Xu
- Kay Chen Tan

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2015-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-02T09:50:57.853249Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 2015 Annual Conference on Genetic and Evolutionary
  Computation*'
publication_short: ''

doi: 10.1145/2739480.2754714

abstract: Proper tuning of control parameters is critical to the performance of a
  multi-objective evolutionary algorithm (MOEA). However, the developments of tuning
  methods for multi-objective optimization are insufficient compared to single-objective
  optimization. To circumvent this issue, this paper proposes a novel framework that
  can self-adapt the parameter values from an objective-based perspective. Optimal
  parametric setups for each objective will be efficiently estimated by combining
  single-objective tuning methods with a grouping mechanism. Subsequently, the position
  information of individuals in objective space is utilized to achieve a more efficient
  adaptation among multiple objectives. The new framework is implemented into two
  classical Differential-Evolution-based MOEAs to help to adapt the scaling factor
  F in an objective-wise manner. Three state-of-the-art single-objective tuning methods
  are applied respectively to validate the robustness of the proposed mechanisms.
  Experimental results demonstrate that the new framework is effective and robust
  in solving multi-objective optimization problems.

# Summary. An optional shortened abstract.
summary: ''

tags:
- differential evolution
- multi-objective optimization
- parameter tuning

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
  url: https://doi.org/10.1145/2739480.2754714
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
