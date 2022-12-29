+++
title = "Interpolating Classifiers Make Few Mistakes"
date = 2022-12-29
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Tengyuan Liang", "Benjamin Recht"]

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
publication = "Journal of Machine Learning Research"
publication_short = "*Journal of Machine Learning Research*"

# Abstract and optional shortened version.
abstract = "This paper provides elementary analyses of the regret and generalization of minimum-norm interpolating classifiers (MNIC). The MNIC is the function of smallest Reproducing Kernel Hilbert Space norm that perfectly interpolates a label pattern on a finite data set. We derive a mistake bound for MNIC and a regularized variant that holds for all data sets. This bound follows from elementary properties of matrix inverses. Under the assumption that the data is independently and identically distributed, the mistake bound implies that MNIC generalizes at a rate proportional to the norm of the interpolating solution and inversely proportional to the number of data points. This rate matches similar rates derived for margin classifiers and perceptrons. We derive several plausible generative models where the norm of the interpolating classifier is bounded or grows at a rate sublinear in $n$. We also show that as long as the population class conditional distributions are sufficiently separable in total variation, then MNIC generalizes with a fast rate."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
#   projects = ["stat-learning", "high-dim-statistics", "deep-learning"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Machine Learning (stat.ML)", "Learning (cs.LG)", "Statistics Theory (math.ST)", "Numerical Analysis (cs.NA)"]

# Links (optional).
url_pdf = "pdf/preprint-Liang-Recht-21.pdf"
url_preprint = "https://arxiv.org/abs/2101.11815"
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
