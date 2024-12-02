---
title: 'Shortest Edit Path Crossover: A Theory-driven Solution to the Permutation
  Problem in Evolutionary Neural Architecture Search'

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

date: 2023-07-01

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-11-30T14:37:06.836948Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the 40th International Conference on Machine Learning (ICML 2023)*'
publication_short: ''

doi: ''

abstract: 'Population-based search has recently emerged as a possible alternative to Reinforcement Learning (RL) for black-box neural architecture search (NAS). It performs well in practice even though it is not theoretically well understood. In particular, whereas traditional population-based search methods such as evolutionary algorithms (EAs) draw much power from crossover operations, it is difficult to take advantage of them in NAS. The main obstacle is believed to be the permutation problem: The mapping between genotype and phenotype in traditional graph representations is many-to-one, leading to a disruptive effect of standard crossover. This paper presents the first theoretical analysis of the behaviors of mutation, crossover and RL in black-box NAS, and proposes a new crossover operator based on the shortest edit path (SEP) in graph space. The SEP crossover is shown theoretically to overcome the permutation problem, and as a result, have a better expected improvement compared to mutation, standard crossover and RL. Further, it empirically outperform these other methods on state-of-the-art NAS benchmarks. The SEP crossover therefore allows taking full advantage of population-based search in NAS, and the underlying theory can serve as a foundation for deeper understanding of black-box NAS methods in general.'

# Summary. An optional shortened abstract.
summary: ''

tags: [ICML 2023]

# Display this page in a list of Featured pages?
featured: true

# Links
url_pdf: 'https://arxiv.org/pdf/2210.14016'
url_code: 'https://github.com/cognizant-ai-labs/sepx-paper'
url_dataset: ''
url_poster: 'https://nn.cs.utexas.edu/downloads/posters/qiu.icml23.pdf'
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://slideslive.com/39003842/shortest-edit-path-crossover-a-theorydriven-solution-to-the-permutation-problem-in-evolutionary-neural-architecture-search?ref=speaker-22915'

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
---

