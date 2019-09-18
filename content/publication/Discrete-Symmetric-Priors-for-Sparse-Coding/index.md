+++
title = "Discrete Symmetric Priors for Sparse Coding"
date = "2011-10-04"

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Georgios Exarchakis", "Marc Henniges","Jörg Lücke"]

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

# Tags
tags = ["unsupervised learning", "sparse coding", "natural image statistics"]

# Publication name and optional abbreviated version.
publication = "In  *Bernstein Conference* 2011. "
publication_short = "In *Bernstein Conference* "

# Abstract and optional shortened version.
abstract = "A standard model to explain the receptive fields of simple cells in the primary visual cortex is Sparse Coding (SC) [1]. However, the update equations used to train this model are not derivable in closed form. As a consequence, most state-of-the-art sparse coding versions use the MAP estimate for inference and training. Furthermore, it is not known if continuous hidden variables represent the best choice, e.g., for sparse coding as model for V1 processing. By using binary hidden variables, for instance, Binary Sparse Coding (BSC) [2], or [3], alternative priors with discrete hidden variables have been investigated in the past. The binary hidden space allows for analytically derivable update rules in closed-form and thus does not require a MAP estimation. However, in contrast, e.g., to Laplace priors, the Bernoulli distribution is not symmetric and its mean is not zero. To study the implications of discrete hidden variables independent of differences in prior symmetries, we, in this work, investigate a generative model with symmetrical and discrete prior distribution. Furthermore, a generative model with such a prior directly connects to recent sparse coding versions with hard-sparseness constraint (compare, e.g., [4]). As model for a discrete and symmetric prior, we use a multinomial distribution for hidden variables that can take on the values -1,0 and 1. In numerical experiments, we train the model using Expectation Truncation (ET) [5], a variational EM method which uses a preselection of hidden variables to increase learning efficiency. To show the effectiveness of the algorithm, we adjusted the linear bars test described in the BSC paper to fit our model. In the linear bars test the model was able to learn both the basis functions and the data noise. The linear bars test also provides considerable evidence that training the parameters using ET reduces the number of local optima. In experiments on more realistic data, we applied the algorithm to 50,000 large scale image patches (26x26 pixels) taken from the van Hateren image data base [6] and pre-processed with pseudo-whitening, using massive parallel computing. In this experiment, we obtained Gabor-like basis functions with similar properties as reported for receptive fields of V1 simple cells. We analyze the obtained Gabors and discuss differences and similarities to different sparse coding versions in the literature."
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
#url_pdf = "https://link.springer.com/chapter/10.1007/978-3-642-28551-6_26"
#url_citation = "#"
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
highlight = false

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
#[image]
#image = "headers/bubbles-wide.jpg"
#caption = "publication :smile:"

+++

<!-- More detail can easily be written here using *Markdown* and $\rm \LaTeX$ math code. -->
