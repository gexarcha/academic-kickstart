+++
title = "Truncated Variational Sampling for ‘Black Box’ Optimization of Generative Models"
date = 2018-06-30T14:38:58+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Jörg Lücke","Zhenwen Dai","Georgios Exarchakis"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference proceedings
# 2 = Journal
# 3 = Work in progress
# 4 = Technical report
# 5 = Book
# 6 = Book chapter
publication_types = ["1"]

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[header]
  #image="bubbles-wide.jpg"
  #caption = "publication :smile:"

# Tags and categories
categories = []
tags = ["machine learning", "graphical models", "unsupervised learning", "optimization"]

# Publication name and optional abbreviated version.
publication = "In  *International Conference on Latent Variable Analysis and Signal Separation* 2018."
publication_short = "In *LVA/ICA*"


# Abstract and optional shortened version.
abstract = "We investigate the optimization of two probabilistic generative models with binary latent variables using a novel variational EM approach. The approach distinguishes itself from previous variational approaches by using latent states as variational parameters. Here we use efficient and general purpose sampling procedures to vary the latent states, and investigate the black box applicability of the resulting optimization procedure. For general purpose applicability, samples are drawn from approximate marginal distributions of the considered generative model as well as from the model’s prior distribution. As such, variational sampling is defined in a generic form, and is directly executable for a given model. As a proof of concept, we then apply the novel procedure (A) to Binary Sparse Coding (a model with continuous observables), and (B) to basic Sigmoid Belief Networks (which are models with binary observables). Numerical experiments verify that the investigated approach efficiently as well as effectively increases a variational free energy objective without requiring any additional analytical steps."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = "bboptim_bsc_bars_combination.eps"

# Is this a featured publication? (true/false)
featured = true

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep learning"]` references `content/project/deep-learning.md`.
# projects = []

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
# tags = []

# Links (optional).
url_pdf = "https://arxiv.org/pdf/1712.08104.pdf"
# url_preprint = ""
# url_code = ""
# url_dataset = ""
# url_project = ""
# url_slides = ""
# url_video = ""
# url_poster = ""
# url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Does this page require source code highlighting? (true/false)
highlight = false


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  #"bubbles-wide.jpg"
  # Caption (optional)
  #caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
