---
title: "How to merge granule GeoTiff data with GDAL"
subtitle: Mosaic and rasterize granule data, with GDAL and R environment.
summary:
authors:
- admin
tags: []
categories: []
date: "2020-02-1122:05:38Z"
lastMod: "2020-02-11T00:00:00Z"
featured: true
draft: true

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

## Step 1: Build mosaic

```bash
gdalbuildvrt mosaic.vrt data/*.tif
```

## Step 2: Convert the mosaic to GeoTiff file.

```bash
gdal_translate -of GTiff \
 -co "COMPRESS=JPEG" \
 -co "PHOTOMETRIC=YCBCR" \
 -co "TILED=YES" \
 mosaic.vrt mosaic.tif
```



```bash
gdal_translate -of GTiff \
 mosaic.vrt mosaic.tif
```



References:

https://gis.stackexchange.com/questions/230553/merging-all-tiles-from-one-directory-using-gdal

http://blog.cleverelephant.ca/2015/02/geotiff-compression-for-dummies.html
