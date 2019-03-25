+++
title = "Graph Computing based Distributed Fast Decoupled Power Flow Analysis"
date = 2019-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Chen Yuan, Yi Lu, Wei Feng, Guangyi Liu, Renchang Dai, Yachen Tang, Zhiwei Wang"]

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
publication = "2019 IEEE Power & Energy Society General Meeting"
#publication_short = "In *SITIS*"

# Abstract and optional shortened version.
abstract = "Power flow analysis plays a fundamental and critical role in the energy management system (EMS). It is required to well accommodate large and complex power system. To achieve a high performance and accurate power flow analysis, a graph computing based distributed power flow analysis approach is proposed in this paper. Firstly, a power system network is divided into multiple areas. Slack buses are selected for each area and, at each SCADA sampling period, the inter-area transmission line power flows are equivalently allocated as extra load injections to corresponding buses. Then, the system network is converted into multiple independent areas. In this way, the power flow analysis could be conducted in parallel for each area and the solved system states could be guaranteed without compromise of accuracy. Besides, for each area, graph computing based fast decoupled power flow (FDPF) is employed to quickly analyze system states. IEEE 118-bus system and MP 10790-bus system are employed to verify the results accuracy and present the promising computation performance of the proposed approach."
abstract_short = "To achieve a high performance and accurate power flow analysis, a graph computing based distributed power flow analysis approach is proposed in this paper."

# Is this a featured publication? (true/false)
featured = false

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example-slides"

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = []

# Links (optional).
url_pdf = "https://arxiv.org/ftp/arxiv/papers/1902/1902.06893.pdf"
url_preprint = ""
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

# Digital Object Identifier (DOI)
# doi = ""

# Does this page contain LaTeX math? (true/false)
math = true

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++
