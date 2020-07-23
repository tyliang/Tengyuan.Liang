+++
title = "Interaction Matters: A Note on Non-asymptotic Local Convergence of Generative Adversarial Networks"
date = 2019-01-02
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["**Tengyuan Liang**", "James Stokes"]

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
publication = "International Conference on Artificial Intelligence and Statistics (AISTATS), PMLR vol.89, 907-915"
publication_short = "*International Conference on Artificial Intelligence and Statistics (AISTATS)*"

# Abstract and optional shortened version.
abstract = "Motivated by the pursuit of a systematic computational and algorithmic understanding of Generative Adversarial Networks (GANs), we present a simple yet unified non-asymptotic local convergence theory for smooth two-player games, which subsumes several discrete-time gradient-based saddle point dynamics. The analysis reveals the surprising nature of the off-diagonal interaction term as both a blessing and a curse. On the one hand, this interaction term explains the origin of the slow-down effect in the convergence of Simultaneous Gradient Ascent (SGA) to stable Nash equilibria. On the other hand, for the unstable equilibria, exponential convergence can be proved thanks to the interaction term, for three modified dynamics which have been proposed to stabilize GAN training: Optimistic Mirror Descent (OMD), Consensus Optimization (CO) and Predictive Method (PM). The analysis uncovers the intimate connections among these stabilizing techniques, and provides detailed characterization on the choice of learning rate."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   projects = ["deep-learning", "stochastic-optimization"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Learning (cs.LG)", "Computer Science and Game Theory (cs.GT)", "Machine Learning (stat.ML)", "Optimization and Control (math.OC)"]

# Links (optional).
url_pdf = "http://proceedings.mlr.press/v89/liang19b.html"
url_preprint = "https://arxiv.org/abs/1802.06132"
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
