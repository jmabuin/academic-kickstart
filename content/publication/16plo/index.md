---
title: "SparkBWA: Speeding Up the Alignment of High-Throughput DNA Sequencing Data"
date: 2016-05-16
draft: false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- admin
- Juan C. Pichel
- Tomás F. Pena
- Jorge Amigo

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
publication: "SparkBWA: Speeding Up the Alignment of High-Throughput DNA Sequencing Data"
publication_short: "In *Plos One*"

# Abstract and optional shortened version.
abstract: "Next-generation sequencing (NGS) technologies have led to a huge amount of genomic data that need to be analyzed and interpreted. This fact has a huge impact on the DNA sequence alignment process, which nowadays requires the mapping of billions of small DNA sequences onto a reference genome. In this way, sequence alignment remains the most time-consuming stage in the sequence analysis workflow. To deal with this issue, state of the art aligners take advantage of parallelization strategies. However, the existent solutions show limited scalability and have a complex implementation. In this work we introduce SparkBWA, a new tool that exploits the capabilities of a big data technology as Spark to boost the performance of one of the most widely adopted aligner, the Burrows-Wheeler Aligner (BWA). The design of SparkBWA uses two independent software layers in such a way that no modifications to the original BWA source code are required, which assures its compatibility with any BWA version (future or legacy). SparkBWA is evaluated in different scenarios showing noticeable results in terms of performance and scalability. A comparison to other parallel BWA-based aligners validates the benefits of our approach. Finally, an intuitive and flexible API is provided to NGS professionals in order to facilitate the acceptance and adoption of the new tool. The source code of the software described in this paper is publicly available at https://github.com/citiususc/SparkBWA, with a GPL3 license."
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
tags: ["Big Data", "Genomics", "Spark", "BWA", "Alignment", "HPC"]

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
doi: "10.1371/journal.pone.0155461"

# Does this page contain LaTeX math? (true/false)
math: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # Caption (optional)
  caption: "Algorithm."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: ""
---
