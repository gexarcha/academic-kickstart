+++
title = "Probabilistic Models for Invariant Representations and Transformations"
date = "2016-12-01"
# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Georgios Exarchakis"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["0"]

# Tags
tags = ["unsupervised learning", "sparse coding", "natural image statistics", "invariant representations", "neural networks"]

# Publication name and optional abbreviated version.
publication = "Doctoral dissertation,  BIS der Universität Oldenburg 2016."
publication_short = "Doctoral Dissertation"

# Abstract and optional shortened version.
abstract = "The central task of machine learning research is to extract regularities from data. These regularities are often subject to transformations that arise from the complexity of the process that generates the data. There has been a lot of effort towards creating data representations that are invariant to such transformations. However, most research towards learning invariances does not model the transformations explicitly. My research is focused towards modeling data in ways that separate their “content” from the potential “transformations” it undergoes. I primarily used a probabilistic generative framework due to its high expressive power and the belief that any potential representation will be subject to uncertainty. To model data content I focused on sparse coding techniques due to their ability to extract highly specialized dictionaries. I defined and implemented a discrete sparse coding model that models the presence/absence of a dictionary element subject to finite set of scaling transformations. I extended the discrete sparse coding model with an explicit representation for temporal shifts that learns time invariant representations for the data without loss of temporal alignment. In an attempt to create a more general model for data transformations, I defined a neural network that uses gating units to encode transformations from pairs of datapoints. Furthermore, I defined a non-linear dynamical system that expresses the dynamics in terms of a bilinear transformation that combines the previous state and a variable that encodes the transformation to generate the current state. In order to examine the behavior of these models in practice I tested them with on a variety of tasks. Almost always, I tested the models on recovering parameters from artificially generated data. Furthermore, I discovered interesting properties in the encoding of natural images, extra-cellular neural recordings, and audio data."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "http://oops.uni-oldenburg.de/3375/1/exapro16.pdf"
url_citation = "#"
#url_preprint = ""
#url_code = "#"
#url_dataset = "#"
#url_project = "#"
#url_slides = "#"
#url_video = "#"
#url_poster = "#"
#url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
#url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does the content use math formatting?
math = true

# Does the content use source code highlighting?
highlight = true


+++

<!-- More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code. -->
