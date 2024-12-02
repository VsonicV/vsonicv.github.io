---
title: Simple genetic operators are universal approximators of probability distributions
  (and other advantages of expressive encodings)

# Authors
# A YAML list of author names
# If you created a profile for a user (e.g. the default `admin` user at `content/authors/admin/`), 
# write the username (folder name) here, and it will be replaced with their full name and linked to their profile.
authors:
- Elliot Meyerson
- Xin Qiu
- Risto Miikkulainen

# Author notes (such as 'Equal Contribution')
# A YAML list of notes for each author in the above `authors` list
author_notes: []

date: '2022-01-01'

# Date to publish webpage (NOT necessarily Bibtex publication's date).
publishDate: '2024-12-02T09:43:08.231420Z'

# Publication type.
# A single CSL publication type but formatted as a YAML list (for Hugo requirements).
publication_types:
- paper-conference

# Publication name and optional abbreviated publication name.
publication: '*Proceedings of the Genetic and Evolutionary Computation Conference*'
publication_short: ''

doi: 10.1145/3512290.3528746

abstract: 'This paper characterizes the inherent power of evolutionary algorithms.
  This power depends on the computational properties of the genetic encoding. With
  some encodings, two parents recombined with a simple crossover operator can sample
  from an arbitrary distribution of child phenotypes. Such encodings are termed expressive
  encodings in this paper. Universal function approximators, including popular evolutionary
  substrates of genetic programming and neural networks, can be used to construct
  expressive encodings. Remarkably, this approach need not be applied only to domains
  where the phenotype is a function: Expressivity can be achieved even when optimizing
  static structures, such as binary vectors. Such simpler settings make it possible
  to characterize expressive encodings theoretically: Across a variety of test problems,
  expressive encodings are shown to achieve up to super-exponential convergence speed-ups
  over the standard direct encoding. The conclusion is that, across evolutionary computation
  areas as diverse as genetic programming, neuroevolution, genetic algorithms, and
  theory, expressive encodings can be a key to understanding and realizing the full
  power of evolution.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- expressive encodings
- genetic algorithms
- universal approximation

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
  url: https://doi.org/10.1145/3512290.3528746
---

Add the **full text** or **supplementary notes** for the publication here using Markdown formatting.
