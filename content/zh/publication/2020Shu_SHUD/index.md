+++
title = "Simulator for Hydrologic Unstructured Domains (SHUD v1.0): Numerical modeling of watershed hydrology with the finite volume method"
date = 2020-01-12T00:00:00

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Shu, Lele", "Ullrich, Paul", "Duffy, Christopher"]

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
publication = "Geoscientific Model Development"
publication_short = "GME"

# Abstract.
abstract = ""

# Summary. An optional shortened abstract.
summary = "This paper introduces the design of SHUD, from the conceptual and mathematical description of hydrological processes in a watershed to computational structures. To demonstrate and validate the model performance, we employ three hydrological experiments: the V-Catchment experiment, Vauclin's experiment, and a study of the Cache Creek Watershed in northern California, USA."

# Digital Object Identifier (DOI)
doi = "10.5194/gmd-13-2743-2020"

# Is this a featured publication? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["SHUD", "Hydrological Model", "Finite Volume Method", "Watershed", "Numerical methods", "Hydrology"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Links (optional).
# url_pdf = ""
# url_preprint = ""
# url_code = "#"
# url_dataset = "#"
# url_project = ""
# url_slides = "#"
# url_video = "#"
# url_poster = "#"
# url_source = "#"

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Does this page contain LaTeX math? (true/false)
math = false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = ""

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

Hydrologic modeling is an essential strategy for understanding and predicting natural flows, particularly where observations are lacking in either space or time or where complex terrain leads to a disconnect in the characteristic time and space scales of overland and groundwater flow. However, significant difficulties remain for the development of efficient and extensible modeling systems that operate robustly across complex regions. This paper introduces the Simulator for Hydrologic Unstructured Domains (SHUD), an integrated, multiprocess, multiscale, flexible-time-step model, in which hydrologic processes are fully coupled using the finite volume method. SHUD integrates overland flow, snow accumulation/melt, evapotranspiration, subsurface flow, groundwater flow, and river routing, thus allowing physical processes in general watersheds to be realistically captured. SHUD incorporates one-dimensional unsaturated flow, two-dimensional groundwater flow, and a fully connected river channel network with hillslopes supporting overland flow and baseflow.

The paper introduces the design of SHUD, from the conceptual and mathematical description of hydrologic processes in a watershed to the model's computational structures. To demonstrate and validate the model performance, we employ three hydrologic experiments: the V-catchment experiment, Vauclin's experiment, and a model study of the Cache Creek Watershed in northern California. Ongoing applications of the SHUD model include hydrologic analyses of hillslope to regional scales (1 m2 to 106 km2), water resource and stormwater management, and interdisciplinary research for questions in limnology, agriculture, geochemistry, geomorphology, water quality, ecology, climate and land-use change. The strength of SHUD is its flexibility as a scientific and resource evaluation tool where modeling and simulation are required.

**How to cite.**  Shu, L., Ullrich, P. A., and Duffy, C. J.: Simulator for Hydrologic Unstructured Domains (SHUD v1.0): numerical modeling of watershed hydrology with the finite volume method, Geosci. Model Dev., 13, 2743–2762, https://doi.org/10.5194/gmd-13-2743-2020, 2020.
