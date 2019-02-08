+++
title = "Exploration of Graph Computing in Power System State Estimation"
date = 2018-09-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Chen Yuan, Yuqi Zhou, Guofang Zhang, Guangyi Liu, Renchang Dai, Xi Chen, Zhiwei Wang"]

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
publication = "2018 IEEE Power & Energy Society General Meeting"
#publication_short = "In *SITIS*"

# Abstract and optional shortened version.
abstract = "With the increased complexity of power systems due to the integration of smart grid technologies and renewable energy resources, more frequent changes have been introduced to system status, and the traditional serial mode of state estimation algorithm cannot well meet the restrict time-constrained requirement for the future dynamic power grid, even with advanced computer hardware. To guarantee the grid reliability and minimize the impacts caused by system status fluctuations, a fast, even SCADA-rate, state estimator is urgently needed. In this paper, a graph based power system modeling is firstly explored and a graph computing based state estimation is proposed to speed up its performance. The power system is represented by a graph, which is a collection of vertices and edges, and the measurements are attributes of vertices and edges. Each vertex can independently implement local computation, like formulations of the node-based H matrix, gain matrix and righthand-side (RHS) vector, only with the information on its connected edges and neighboring vertices. Then, by taking advantages of graph database, these node-based data are conveniently collected and stored in the compressed sparse row (CSR) format avoiding the complexity and heaviness introduced by the sparse matrices. With communications and synchronization, centralized computation of solving the weighted least square (WLS) state estimation is completed with hierarchical parallel computing. The proposed strategy is implemented on a graph database platform. The testing results of IEEE 14-bus, IEEE 118-bus systems and a provincial system in China verify the accuracy and high-performance of the proposed methodology."
abstract_short = "In this paper, a graph based power system modeling is firstly explored and a graph computing based state estimation is proposed to speed up its performance."

# Is this a featured publication? (true/false)
featured = true

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
url_pdf = "https://ieeexplore.ieee.org/document/8586535"
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
doi = "10.1109/PESGM.2018.8586535"

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
