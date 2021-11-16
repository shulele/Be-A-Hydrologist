---
title: 使用R语言计算、绘制和动画演示物体、天体在太空的运行状况.
subtitle: The project to plot planets/objects in space and orbital movement.
summary:
authors:
- admin
tags: []
categories: []
date: "2019-01-29T00:00:00Z"
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
I planed to write an R package and submit on CRAN, that can plot the planets orbiting in Solar System, or satellite/moon orbiting around earth. That package must plot the moving planets, the moon, moon phase and satellite in 2D or 3D canvas. In future, it may calculate the orbit based on orbit mechanics.

My son loves the song “The wheels on the bus go round and round“, and he has an obsession on planets. He asks mommy play the solar system documentary every night when we ask him to brush his teeth.  So I decided to plot the moving planets in solar system for him with the scientific knowledge I know.

|My son is obsessed by the planets and stars|
|:--|
| ![classroom.jpg](photo.png) |

Another motivation is from the Chinese lunar exploration, Chang-E 5 landing on far-side of the moon.  Lots of people discussed it and were fuddled on the rotation of moon and relation between the earth and the moon.

Furthermore, I kept thinking the Chinese semi-lunar calendar for many years, I know the founder mental logic and algorithm of the calendar in my mind, but never scratched the equations and numbers in paper yet.  This calendar is determined by the moon phase and the position of the earth in orbit. Definitely the solver in papers are more rousted in my brain.

Let’s see what I got, by now.

|The idea of the Moon and the Sun are moving around the Earth, when we assume the earth is the center of system. The orbital period of the moon is 27.321 day, but the synodic period is 29.53 day, that because the sun moves 27.321/365.25 in its sun’s orbit when the moon moves in the moon’s orbit. It requires 2.2 days to let the sun and the moon to face-to-face again.|
|:--|
| ![classroom.jpg](Moon0.png) |


|The position of the Moon and the Sun in an earth year (365 day). The right legend shows the moon phase in 30 days. The concentric orbits are numbers of the moon periods.|
|:--|
| ![classroom.jpg](Moon_year365.png) |