+++
title = "Graph Computing based Distributed Fast Decoupled Power Flow Analysis"
date = 2019-08-01T00:00:00
draft = false

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Chen Yuan", "Yi Lu", "Wei Feng", "Guangyi Liu", "Renchang Dai", "Yachen Tang", "Zhiwei Wang"]

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
abstract = "This paper proposes a graph computation based sequential power flow calculation method for Line Commutated Converter (LCC) based large-scale AC/DC systems to achieve a high computing performance. Based on the graph theory, the complex AC/DC system is first converted to a graph model and stored in a graph database. Then, the hybrid system is divided into several isolated areas with graph partition algorithm by decoupling AC and DC networks. Thus, the power flow analysis can be executed in parallel for each independent area with the new selected slack buses. Furthermore, for each area, the node-based parallel computing (NPC) and hierarchical parallel computing (HPC) used in graph computation are employed to speed up fast decoupled power flow (FDPF). Comprehensive case studies on the
IEEE 300-bus, polished South Carolina 12,000-bus system and a China 11,119-bus system are performed to demonstrate the accuracy and efficiency of the proposed method."
#abstract_short = "This paper employs vertex contraction to eliminate zero-impedance branch and combines two iterative methods to improve the convergence"

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
url_pdf = "https://ieeexplore.ieee.org/document/8601938"
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
doi = "10.1109/POWERCON.2018.8601938"

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
