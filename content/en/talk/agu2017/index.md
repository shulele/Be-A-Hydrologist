+++
title = "Coupling Cellular Automata Land Use Change with Distributed Hydrologic models"
date = 2017-12-01T00:00:00  # Schedule page publish date (not talk date).

# Authors. Comma separated list, e.g. `["Bob Smith", "David Jones"]`.
authors = ["Lele Shu", "Christopher Duffy"]

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
time_start = 2017-12-12T13:00:00
time_end = 2017-12-12T18:00:00
all_day = false

# Location of event.
location = "New Orleans LA, United States"

# Name of event and optional event URL.
event = "NG31B-0170 "
#event_url = "https://example.org"

# Abstract. What's your talk about?
abstract = " There has been extensive research on LUC modeling with broad applications to simulating urban growth and changing demographic patterns across multiple scales. The importance of land conversion is a critical issue in watershed scale studies and is generally not treated in most watershed modeling approaches.  <br>In this study we apply spatially explicit hydrologic and landuse change models and the Conestoga Watershed in Lancaster County, Pennsylvania. The Penn State Integrated Hydrologic Model (PIHM) partitions the water balance in space and time over the urban catchment, the coupled Cellular Automata Land Use Change model (CALUC) dynamically simulates the evolution of land use classes based on physical measures associated with population change and land use demand factors. <br>The CALUC model is based on iteratively applying discrete rules to each individual spatial cell.  The essence the CA modeling involves calculation of the Transition Potential (TP) for conversion of a grid cell from one land use class to another. This potential includes five factors: random perturbation, suitability, accessibility, neighborhood effect, inertia effects and zonal factors. In spite of simplicity, this CALUC model has been shown to be very effective for simulating LUC leading to the emergence of complex spatial patterns. The components of TP are derived from present land use data for landuse reanalysis and for realistic future land use scenarios. <br>For the CALUC we use early-settlement (circa 1790) initial land class values and final or present-day (2010) land classes to calibrate the model. CALUC- PIHM dynamically simulates the hydrologic response of conversion from pre-settlement to present landuse.  The simulations highlight the capability and value of dynamic coupling of catchment hydrology with land use change over long time periods.  Analysis of the simulation uses various metrics such as the distributed water balance, flow duration curves, etc.  to show how deforestation, urbanization and agricultural land development interact for the period 1790- present. "

# Summary. An optional shortened abstract.
summary = "Poster in AGU 2017 Fall meeting"

# Is this a featured talk? (true/false)
featured = true

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Poster", "Landuse change", "Hydrologic Modeling", "PIHM"]

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides = "example-slides"

# Optional filename of your slides within your talk folder or a URL.
url_slides = ""

# Projects (optional).
#   Associate this talk with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = ["internal-project"]

# Links (optional).
# url_pdf = "talk/agu2017/poster.pdf"
url_video = ""
url_code = ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
[image]
  # Caption (optional)
  caption = "Preferences of landuse by various spatial factors"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = "Smart"
+++
