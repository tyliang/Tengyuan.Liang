+++
title = "Statistical Inference for the Population Landscape via Moment Adjusted Stochastic Gradients"
date = 2019-02-17
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Tengyuan Liang**", "Weijie Su"]

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
publication = "Journal of the Royal Statistical Society: Series B (Statistical Methodology), vol.81 (2), 431-456"
publication_short = "*Journal of the Royal Statistical Society: Series B (Statistical Methodology)*"

# Abstract and optional shortened version.
abstract = "Modern statistical inference tasks often require iterative optimization methods to approximate the solution. Convergence analysis from optimization only tells us how well we are approximating the solution deterministically, but overlooks the sampling nature of the data. However, due to the randomness in the data, statisticians are keen to provide uncertainty quantification, or confidence, for the answer obtained after certain steps of optimization. Therefore, it is important yet challenging to understand the sampling distribution of the iterative optimization methods. This paper makes some progress along this direction by introducing a new stochastic optimization method for statistical inference, the moment adjusted stochastic gradient descent. We establish non-asymptotic theory that characterizes the statistical distribution of the iterative methods, with good optimization guarantee. On the statistical front, the theory allows for model misspecification, with very mild conditions on the data. For optimization, the theory is flexible for both the convex and non-convex cases. Remarkably, the moment adjusting idea motivated from ''error standardization'' in statistics achieves similar effect as Nesterov's acceleration in optimization, for certain convex problems as in fitting generalized linear models. We also demonstrate this acceleration effect in the non-convex setting through experiments."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["stochastic-optimization", "stat-learning"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Machine Learning (stat.ML)", "Statistics Theory (math.ST)", "Methodology (stat.ME)", "Optimization and Control (math.OC)"]

# Links (optional).
url_pdf = "pdf/arxiv_mas_grad.pdf"
url_preprint = "https://arxiv.org/abs/1712.07519"
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
