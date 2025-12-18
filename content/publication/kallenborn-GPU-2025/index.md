---
# Documentation: https://wowchemy.com/docs/managing-content/

title: GPU-accelerated homology search with MMseqs2
subtitle: ''
summary: ''
authors:
- Felix Kallenborn
- Alejandro Chacon
- Christian Hundt
- Hassan Sirelkhatim
- Kieran Didi
- Sooyoung Cha
- Christian Dallago
- Milot Mirdita
- Bertil Schmidt
- Martin Steinegger
tags: []
categories: []
date: '2025-09-01'
lastmod: 2025-10-14T03:34:29+09:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2025-10-13T18:34:28.980195Z'
publication_types:
- '2'
abstract: Rapidly growing protein databases demand faster sensitive search tools.
  Here the graphics processing unit (GPU)-accelerated MMseqs2 delivers 6× faster single-protein
  searches than CPU methods on 2 × 64 cores, speeds previously requiring large protein
  batches. For larger query batches, it is the most cost-effective solution, outperforming
  the fastest alternative method by 2.4-fold with eight GPUs. It accelerates protein
  structure prediction with ColabFold 31.8× over the standard AlphaFold2 pipeline
  and protein structure search with Foldseek by 4–27×. MMseqs2-GPU is available under
  an open-source license at https://mmseqs.com/.
publication: '*Nature Methods*'
doi: 10.1038/s41592-025-02819-8
links:
- name: URL
  url: https://www.nature.com/articles/s41592-025-02819-8
---