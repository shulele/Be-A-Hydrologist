---
title: "编译NetCDF"
subtitle:  ""
summary:  ""
authors:
- admin
tags: []
categories: []
date: "2020-03-2222:05:38Z"
lastMod: "2020-03-28T00:00:00Z"
featured: true
draft: ture

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



The following packages are required to build netCDF-C using CMake.

- netCDF-C Source Code

- CMake version 2.8.12 or greater.

- Optional Requirements:

  - HDF5 Libraries for netCDF4/HDF5 support.
  - libcurl for DAP support.
  - PnetCDF libraries for parallel I/O support to classic netCDF files



If you have libraries installed in a custom directory, you may need to specify the **CMAKE_PREFIX_PATH** variable to tell cmake where the libraries are installed. For example:

> $ cmake [Source Directory] -DCMAKE_PREFIX_PATH=~/

## Building

The compiler can be executed directly with 'make' or the appropriate command for the configurator which was used.

> $ make

Building can also be executed indirectly via cmake:

> $ cmake –build [Build Directory]
