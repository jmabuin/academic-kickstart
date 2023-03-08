---
title: "A Big Data Approach to Metagenomics for All-Food-Sequencing"
date: 2020-03-12
draft: false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors:
- Robin Kobus
- admin
- André Müller
- Sören Lukas Hellmann
- Juan C. Pichel
- Tomás F. Pena
- Andreas Hildebrandt
- Thomas Hankeln
- Bertil Schmidt

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
publication: "A Big Data Approach to Metagenomics for All-Food-Sequencing"
publication_short: "In *BMC Bioinformatics*"

# Abstract and optional shortened version.
abstract: "Background: All-Food-Sequencing (AFS) is an untargeted metagenomic sequencing method that allows for the detection and quantification of food ingredients including animals, plants, and microbiota. While this approach avoids some of the shortcomings of targeted PCR-based methods, it requires the comparison of sequence reads to large collections of reference genomes. The steadily increasing amount of available reference genomes establishes the need for efficient big data approaches.Results: We introduce an alignment-free k-mer based method for detection and quantification of species composition in food and other complex biological matters. It is orders-of-magnitude faster than our previous alignment-based AFS pipeline. In comparison to the established tools CLARK, Kraken2, and Kraken2+Bracken it is superior in terms of false-positive rate and quantification accuracy. Furthermore, the usage of an efficient database partitioning scheme allows for the processing of massive collections of reference genomes with reduced memory requirements on a workstation (AFS-MetaCache) or on a Spark-based compute cluster (MetaCacheSpark).Conclusions: We present a fast yet accurate screening method for whole genome shotgun sequencing-based biosurveillance applications such as food testing. By relying on a big data approach it can scale efficiently towards large-scale collections of complex eukaryotic and bacterial reference genomes. AFS-MetaCache and MetaCacheSpark are suitable tools for broad-scale metagenomic screening applications. They are available at https://muellan.github.io/metacache/afs.html (C++ version for a workstation) and https://github.com/jmabuin/MetaCacheSpark (Spark version for big data clusters)."
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
tags: ["Big Data", "Metagenomics", "All Food Sequencing", "AFS", "HPC"]

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
#url_custom: [{name = "Custom Link", url = "http://example.org"}]

# Digital Object Identifier (DOI)
doi: "10.1186/s12859-020-3429-6"

# Does this page contain LaTeX math? (true/false)
math: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # Caption (optional)
  caption: "Database construction algorithm used by MetaCacheSpark."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: ""
---
