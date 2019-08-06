+++
title = "Computational and Statistical Boundaries for Submatrix Localization in a Large Noisy Matrix"
date = 2017-08-01
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["T. Tony Cai", "**Tengyuan Liang**", "Alexander Rakhlin"]

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
publication = "The Annals of Statistics, vol.45 (4), 1403-1430"
publication_short = "*The Annals of Statistics*"

# Abstract and optional shortened version.
abstract = "We study in this paper computational and statistical boundaries for submatrix \\textit{localization}. Given one observation of (one or multiple non-overlapping) signal submatrix (of magnitude $\\lambda$ and size $k_m \\times k_n$) embedded in a large noise matrix (of size $m \\times n$), the goal is to optimal identify the support of the signal submatrix computationally and statistically. Two transition thresholds for the signal to noise ratio $\\lambda/\\sigma$ are established in terms of $m$, $n$, $k_m$ and $k_n$. The first threshold, $\\sf SNR_c$, corresponds to the computational boundary. We introduce a new linear time spectral algorithm that identifies the submatrix with high probability when the signal strength is above the threshold $\\sf SNR_c$. Below this threshold, it is shown that no polynomial time algorithm can succeed in identifying the submatrix, under the \\textit{hidden clique hypothesis}.  The second threshold, $\\sf SNR_s$, captures the statistical boundary, below which no method can succeed in localization with probability going to one in the minimax sense. The exhaustive search method successfully finds the submatrix above this threshold. In marked contrast to submatrix detection and sparse PCA, the results show an interesting phenomenon that $\\sf SNR_c$ is \\textit{always} significantly larger than $\\sf SNR_s$ under the sub-Gaussian error model, which implies an essential gap between statistical optimality and computational efficiency for submatrix localization."
abstract_short = ""

# Featured image thumbnail (optional)
image_preview = ""

# Is this a selected publication? (true/false)
selected = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter the filename (excluding '.md') of your project file in `content/project/`.
#   E.g. `projects = ["deep-learning"]` references `content/project/deep-learning.md`.
projects = ["computation-statistics-boundaries"]

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Statistics Theory (math.ST)", "Machine Learning (stat.ML)"]

# Links (optional).
url_pdf = "https://projecteuclid.org/euclid.aos/1498636861"
url_preprint = "https://arxiv.org/abs/1502.01988"
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
