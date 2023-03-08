---
title: "VeryFastTree: speeding up the estimation of phylogenies for large alignments through parallelization and vectorization strategies"
date: 2020-06-23
draft: false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- César Piñeiro
- admin
- Juan C. Pichel

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types: ["2"]

# Publication name and optional abbreviated version.
publication: "VeryFastTree: speeding up the estimation of phylogenies for large alignments through parallelization and vectorization strategies"
publication_short: "In *Bioinformatics*"

# Abstract and optional shortened version.
abstract: "Motivation: FastTree-2 is one of the most successful tools for inferring large phylogenies. With speed at the core of its design, there are still important issues in the FastTree-2 implementation that harm its performance and scalability. To deal with these limitations we introduce VeryFastTree, a highly-tuned implementation of the FastTree-2 tool that takes advantage of parallelization and vectorization strategies to boost performance.Results: VeryFastTree is able to construct a tree on a standard server using double precision arithmetic from an ultra-large 330k alignment in only 4.5 hours, which is 7.8× and 3.5× faster than the sequential and best parallel FastTree-2 times, respectively.Availability: VeryFastTree is available at the GitHub repository: https://github.com/citiususc/veryfasttree."
# abstract_short: ""

# Is this a featured publication? (true/false)
featured: false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects: ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags: ["HPC", "Genomics", "trees"]

# Links (optional).
#url_pdf: ""
#url_preprint: "http://hdl.handle.net/2183/19190"
#url_code: "#"
#url_dataset: "#"
#url_project: ""
#url_slides: "#"
#url_video: "#"
#url_poster: "#"
#url_source: "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi: "10.1093/bioinformatics/btaa582"

# Does this page contain LaTeX math? (true/false)
math: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # Caption (optional)
  caption: "A tree."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: ""
---
