+++
title = "Discrete Sparse Coding"
date = "2017-11-01"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Georgios Exarchakis", "Jörg Lücke"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["2"]

# Tags
tags = ["unsupervised learning", "sparse coding", "natural image statistics"]

# Publication name and optional abbreviated version.
publication = "In *Neural Computation* Volume 29 | Issue 11 | November 2017| p.2979-3013"
publication_short = "In *NeCo*"

# Abstract and optional shortened version.
abstract = "Sparse coding algorithms with continuous latent variables have been the subject of a large number of studies. However, discrete latent spaces for sparse coding have been largely ignored. In this work, we study sparse coding with latents described by discrete instead of continuous prior distributions. We consider the general case in which the latents (while being sparse) can take on any value of a finite set of possible values and in which we learn the prior probability of any value from data. This approach can be applied to any data generated by discrete causes, and it can be applied as an approximation of continuous causes. As the prior probabilities are learned, the approach then allows for estimating the prior shape without assuming specific functional forms. To efficiently train the parameters of our probabilistic generative model, we apply a truncated expectation-maximization approach (expectation truncation) that we modify to work with a general discrete prior. We evaluate the performance of the algorithm by applying it to a variety of tasks: (1) we use artificial data to verify that the algorithm can recover the generating parameters from a random initialization, (2) use image patches of natural images and discuss the role of the prior for the extraction of image components, (3) use extracellular recordings of neurons to present a novel method of analysis for spiking neurons that includes an intuitive discretization strategy, and (4) apply the algorithm on the task of encoding audio waveforms of human speech. The diverse set of numerical experiments presented in this letter suggests that discrete sparse coding algorithms can scale efficiently to work with realistic data sets and provide novel statistical quantities to describe the structure of the data."
abstract_short = ""


# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#projects = ["example-external-project"]

# Links (optional).
url_pdf = "files/papers/NECO-09-16-2696R2-PDF.pdf"
#url_pdf = "http://www.mitpressjournals.org/doi/abs/10.1162/neco_a_01015"
#url_citation = "#"
#url_preprint = ""
url_code = "https://github.com/gexarcha/dsc"
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
highlight = false


+++

<!-- More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code. -->
