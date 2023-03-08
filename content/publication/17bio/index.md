---
title: "PASTASpark: multiple sequence alignment meets Big Data"
date: 2017-06-05
draft: false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- admin
- Tomás F. Pena
- Juan C. Pichel

# Publication type.
# Legend:
# 0: Uncategorized
# 1: Conference paper
# 2: Journal article
# 3: Manuscript
# 4: Report
# 5: Book
# 6: Book section
publication_types: ["2"]

# Publication name and optional abbreviated version.
publication: "PASTASpark: multiple sequence alignment meets Big Data"
publication_short: "In *Bioinformatics*"

# Abstract and optional shortened version.
abstract: "Motivation: One basic step in many bioinformatics analyses is the Multiple Sequence Alignment (MSA). One of the state of the art tools to perform MSA is PASTA (Practical Alignments using SATé and TrAnsitivity). PASTA supports multithreading but it is limited to process datasets on shared memory systems. In this work we introduce PASTASpark, a tool that uses the Big Data engine Apache Spark to boost the performance of the alignment phase of PASTA, which is the most expensive task in terms of time consumption. Results: Speedups up to 10× with respect to single-threaded PASTA were observed, which allows to process an ultra-large dataset of 200,000 sequences within the 24-hr limit.Availability: PASTASpark is an Open Source tool available at https://github.com/citiususc/pastaspark"
# abstract_short: ""

# Is this a featured publication? (true/false)
featured: true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
#projects = ["internal-project"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags: ["Big Data", "Genomics", "MSA", "PASTA", "HPC"]

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
doi: "10.1093/bioinformatics/btx354"

# Does this page contain LaTeX math? (true/false)
math: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # Caption (optional)
  caption: "Results."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: ""
---
