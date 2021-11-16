---
title: "2002-201年间美国和全球逐月NDVI的变化动画"
subtitle: Monthly NDVI change in USA and Global from 2002-2017
summary:
authors:
- admin
tags: []
categories: []
date: "2019-06-27T00:00:00Z"
lastMod: "2019-09-05T00:00:00Z"
featured: true
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ""
  focal_point: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

<!-- ![Global NDVI](featured.png) -->

The normalized difference vegetation index (NDVI) is a simple graphical indicator that reflect the greenness and the heath condition of vegetations.

The raw data is from [NASA MOD13A](https://modis.gsfc.nasa.gov/data/dataprod/mod13.php).


- The global NDVI variation from 2002 to 2017.

{{< youtube 7yyPfozr1PU >}}


- The NDVI varies from 2002 to 2017 in US (Continental)
{{< youtube LL0qRwLLd1g >}}
## How to download the rawdata
The code of the monthly NDVI from MODIS dataset is MOD13C2, so type the code below in your terminal and the wget will download all availalble data from server to you local matchine.

```
wget  --user=XXXXX --password=XXXX -r -c -np -x https://e4ftl01.cr.usgs.gov/MOLT/MOD13C2.006/
```

*The R package RoundAndRound and PIHMgisR is used for this data processing and visulization.*
