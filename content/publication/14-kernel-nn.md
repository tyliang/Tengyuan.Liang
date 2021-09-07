+++
title = "Training Neural Networks as Learning Data-adaptive Kernels: Provable Representation and Approximation Benefits"
date = 2021-01-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Xialiang Dou", "Tengyuan Liang"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["2"]

# Publication name and optional abbreviated version.
publication = "Journal of the American Statistical Association (Theory and Methods)"
publication_short = "*Journal of the American Statistical Association (Theory and Methods)*"

# Abstract and optional shortened version.
abstract = "Consider the problem: given data pair $(\\mathbf{x}, \\mathbf{y})$ drawn from a population with $f_\\star(x) = E[ \\mathbf{y} | \\mathbf{x} = x]$, specify a neural network and run gradient flow on the weights over time until any stationarity. How does *$f_t$*, the function computed by the neural network at time t, relate to *$f_\\star$*, in terms of approximation and representation? What are the provable benefits of the adaptive representation by neural networks compared to the pre-specified fixed basis representation in the classical nonparametric literature? We answer the above questions via a dynamic reproducing kernel Hilbert space (RKHS) view indexed by the training process of neural networks. We show that when reaching any local stationarity, gradient flow learns an adaptive RKHS representation, and performs the global least squares projection onto the adaptive RKHS, simultaneously. In addition, we prove that as the RKHS is data-adaptive and task-specific, the residual for *$f_\\star$* lies in a subspace that is smaller than the orthogonal complement of the RKHS, formalizing the representation and approximation benefits of neural networks."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   projects = ["deep-learning", "stat-learning", "high-dim-statistics"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Machine Learning (stat.ML)", "Learning (cs.LG)", "Statistics Theory (math.ST)", "Optimization and Control (math.OC)"]

# Links (optional).
url_pdf = "https://www.tandfonline.com/doi/full/10.1080/01621459.2020.1745812"
url_preprint = "https://arxiv.org/abs/1901.07114"
url_code = ""
url_dataset = ""
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# url_custom = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = true

# Does this page require source code highlighting? (true/false)
highlight = true

# Featured image
# Place your image in the `static/img/` folder and reference its filename below, e.g. `image = "example.jpg"`.
[header]
image = ""
caption = ""

+++
