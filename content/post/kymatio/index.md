+++
title = "Kymatio"
subtitle = ""

# Add a summary to display on homepage (optional).
summary = ""

date = 2019-04-02T13:37:24+02:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Georgios Exarchakis"]

# Is this a featured post? (true/false)
featured = false

# Tags and categories
# For example, use `tags = []` for no tags, or the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["wavelets"]
categories = []

# Does the content use source code highlighting?
highlight = true

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects = ["internal-project"]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Kymatio python package"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Bottom"
+++

[Kymatio](https://kymat.io) is a Python module for computing wavelet and scattering transforms.


It is built on top of PyTorch, but also has a fast CUDA backend via cupy and skcuda.

Use kymatio if you need a library that:

- integrates wavelet scattering in a deep learning architecture,
- supports 1-D, 2-D, and 3-D wavelets, and runs seamlessly on CPU and GPU hardware.
- A brief intro to wavelet scattering is provided in User Guide. For a list of publications see Publications.

<h3>Quick Start</h3>
On Linux or macOS, open a shell and run the instruction of [kymatio](https://github.com/kymatio/kymatio).

In the Python intepreter, you may then call:


{{<highlight python>}}
import kymatio
{{</highlight>}}

which should run without error if the package has been correctly installed.

<h3>Apply 2D scattering to a 32x32 random image</h3>
The following code imports ```torch``` and the ```Scattering2D``` class, which implements the 2D scattering transform. It then creates an instance of this class to compute the scattering transform at scale ```J = 2``` of a ```32x32``` image consisting of Gaussian white noise:

{{<highlight python>}}
import torch
from kymatio import Scattering2D
scattering = Scattering2D(J=2, shape=(32, 32))
x = torch.randn(1, 1, 32, 32)
Sx = scattering(x)
print(Sx.size())
{{</highlight>}}

This should output:

{{<highlight python>}}
torch.Size([1, 1, 81, 8, 8])
{{</highlight>}}

This corresponds to 81 scattering coefficients, each corresponding to an 8x8 image.

Check out the [User Guide](https://www.kymat.io/userguide.html#user-guide) for more scattering transform examples.
