+++
title = "Graph Computation based Power Flow for Large-Scale AC/DC System"
date = 2018-09-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Wei Feng, Chen Yuan, Renchang Dai, Guangyi Liu, Fangxing Li"]

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
publication = "中国电力出版社"
#publication_short = "In *SITIS*"

# Abstract and optional shortened version.
abstract = "In this paper, a graph computation based power flow algorithm is introduced to solve large-scale AC/DC hybrid systems with multi LCC (Line Commuter Converter) based DC grids. The proposed approach is to improve the computational efficiency of constructing related matrices and getting power flow results without changing the conventional sequential iteration method. The hybrid system is modeled as a graph of vertices and edges with info of topology and parameters, thus local computation could be done independently for like formulating mismatch vectors of ΔP,ΔQ,Δ6,ΔV and matrices of B', B only with parameters on its linked edges and adjacent vertices. Then by taking advantages of hierarchical parallel computing, the FDPF (fast decoupled power flow) of AC system, calculation of DC grids and mismatch comparing for each iteration of the sequential method could be done parallelly. This method is implemented on a graph database platform, and tested on IEEE 300-Bus, modified South Carolina 500-Bus system and a Chinese system to verify the accuracy and time-saving performance."
abstract_short = "In this paper, a graph computation based power flow algorithm is introduced to solve large-scale AC/DC hybrid systems with multi LCC (Line Commuter Converter) based DC grids."

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
url_pdf = "https://ieeexplore.ieee.org/document/8602229"
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
doi = "10.1109/POWERCON.2018.8602229"

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
