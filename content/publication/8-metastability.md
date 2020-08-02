+++
title = "Local Optimality and Generalization Guarantees for the Langevin Algorithm via Empirical Metastability"
date = 2018-07-06
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Belinda Tzen", "Tengyuan Liang", "Maxim Raginsky"]

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
publication = "Conference on Learning Theory (COLT), PMLR vol.75, 857-875"
publication_short = "*Conference on Learning Theory (COLT)*"

# Abstract and optional shortened version.
abstract = "We study the detailed path-wise behavior of the discrete-time Langevin algorithm for non-convex Empirical Risk Minimization (ERM) through the lens of metastability, adopting some techniques from \\cite{berglund_gentz_pathwise}. For a particular local optimum of the empirical risk, with an \\textit{arbitrary initialization}, we show that, with high probability, one of the two mutually exclusive events will occur: either the Langevin trajectory ends up somewhere outside the $\\epsilon$-neighborhood of this particular optimum within a short \\textit{recurrence time}; or it enters this $\\epsilon$-neighborhood by the recurrence time and stays there until an exponentially long \\textit{escape time}. We call this phenomenon \\textit{empirical metastability}. This two-timescale characterization aligns nicely with the existing literature in the following two senses. First, the recurrence time is dimension-independent, and resembles the convergence time of deterministic Gradient Descent (GD). However unlike GD, the Langevin algorithm does not require strong conditions on local initialization, and has the possibility of eventually visiting all optima. Second, the scaling of the escape time is consistent with the Eyring-Kramers law, which states that the Langevin scheme will eventually visit all local minima, but it will take an exponentially long time to transit among them. We apply this path-wise concentration result in the context of statistical learning to examine local notions of generalization and optimality."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   projects = ["stochastic-optimization", "stat-learning"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Learning (cs.LG)", "Optimization and Control (math.OC)", "Probability (math.PR)", "Machine Learning (stat.ML)"]

# Links (optional).
url_pdf = "http://proceedings.mlr.press/v75/tzen18a.html"
url_preprint = "https://arxiv.org/abs/1802.06439"
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
