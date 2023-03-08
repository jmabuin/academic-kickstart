---
title: "Big Data in metagenomics: Apache Spark vs MPI"
date: 2020-10-06
draft: false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors: 
- admin
- Nuno Lopes
- Luís Ferreira
- Tomás F. Pena
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
publication: "Big Data in metagenomics: Apache Spark vs MPI"
publication_short: "In *PLoS ONE*"

# Abstract and optional shortened version.
abstract: "The progress of next-generation sequencing has lead to the availability of massive data sets used by a wide range of applications in biology and medicine. This has sparked significant interest in using modern Big Data technologies to process this large amount of information in distributed memory clusters of commodity hardware. Several approaches based on solutions such as Apache Hadoop or Apache Spark, have been proposed. These solutions allow developers to focus on the problem while the need to deal with low level details, such as data distribution schemes or communication patterns among processing nodes, can be ignored. However, performance and scalability are also of high importance when dealing with increasing problems sizes, making in this way the usage of High Performance Computing (HPC) technologies such as the message passing interface (MPI) a promising alternative. Recently, MetaCacheSpark, an Apache Spark based software for detection and quantification of species composition in food samples has been proposed. This tool can be used to analyze high throughput sequencing data sets of metagenomic DNA and allows for dealing with large-scale collections of complex eukaryotic and bacterial reference genome. In this work, we propose MetaCache-MPI, a fast and memory efficient solution for computing clusters which is based on MPI instead of Apache Spark. In order to evaluate its performance a comparison is performed between the original single CPU version of MetaCache, the Spark version and the MPI version we are introducing. Results show that for 32 processes, MetaCache-MPI is 1.65× faster while consuming 48.12% of the RAM memory used by Spark for building a metagenomics database. For querying this database, also with 32 processes, the MPI version is 3.11× faster, while using 55.56% of the memory used by Spark. We conclude that the new MetaCache-MPI version is faster in both building and querying the database and uses less RAM memory, when compared with MetaCacheSpark, while keeping the accuracy of the original implementation."
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
tags: ["HPC", "Metagenomics", "C++"]

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
doi: "10.1371/journal.pone.0239741"

# Does this page contain LaTeX math? (true/false)
math: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # Caption (optional)
  caption: "Reduction algorithm."

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point: ""
---
