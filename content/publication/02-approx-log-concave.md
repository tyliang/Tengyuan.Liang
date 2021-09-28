+++
title = "Escaping the Local Minima via Simulated Annealing: Optimization of Approximately Convex Functions"
date = 2015-07-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Alexandre Belloni", "Tengyuan Liang", "Hariharan Narayanan", "Alexander Rakhlin"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Manuscript
# 4 = Report
# 5 = Book
# 6 = Book section
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "Conference on Learning Theory (COLT), PMLR vol.40, 240–265"
publication_short = "*Conference on Learning Theory (COLT)*"

# Abstract and optional shortened version.
abstract = "We consider the problem of optimizing an approximately convex function over a bounded convex set in $\\mathbb{R}^n$  using only function evaluations. The problem is reduced to sampling from an *approximately* log-concave distribution using the Hit-and-Run method, which is shown to have the same $\\mathcal{O}$ complexity as sampling from log-concave distributions. In addition to extend the analysis for log-concave distributions to approximate log-concave distributions, the implementation of the 1-dimensional sampler of the Hit-and-Run walk requires new methods and analysis. The algorithm then is based on simulated annealing which does not relies on first order conditions which makes it essentially immune to local minima. We then apply the method to different motivating problems. In the context of zeroth order stochastic convex optimization, the proposed method produces an $\\epsilon$-minimizer after $\\mathcal{O}(n^{7.5}\\epsilon^{-2})$ noisy function evaluations  by inducing a $\\mathcal{O}(\\epsilon/n)$-approximately log concave distribution. We also consider in detail the case when the ''amount of non-convexity'' decays towards the optimum of the function. Other applications of the method discussed in this work include private computation of empirical risk minimizers, two-stage stochastic programming, and approximate dynamic programming for online learning."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   projects = ["stochastic-optimization"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Numerical Analysis (cs.NA)", "Learning (cs.LG)", "Optimization and Control (math.OC)"]

# Links (optional).
url_pdf = "http://proceedings.mlr.press/v40/Belloni15.html"
url_preprint = "https://arxiv.org/abs/1501.07242"
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
