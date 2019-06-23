---
title: APIs and JSON with R, and Color Palette Similarity Measures
author: Ryan Benz
date: '2018-09-25'
slug: apis-and-json-with-r-and-color-palette-similarity-measures
categories: []
tags: []
banner: "img/banners/APIColorPalletteWithDate4.png"
---

<b><p style="font-size: 20px; color: blue;">These talks were given on September 25, 2018.</p></b>

== Talk 1 ==

APIs, JSON and R (Peter S.)

Access RESTful APIs using httr, jsonlite and tidyverse packages. Focus will be writing R code.

== Talk 2 ==

Similarity measure in the space of color palettes (Emil H.)

Related to my project of creating a catalog of all available color palettes in r https://github.com/EmilHvitfeldt/ r-color-palettes and its associated r package https://CRAN.R-project.org/package=paletteer I wanted to expand the project to support a higher degree of explorability. There is already quite a bit theory of color similarity and image similarity that will provide useful but unfortunately insufficient. For standard color similarity using some kind of space measure in a perceptual color space will likely give you what you need, but this approach will start to struggle when you need to compare groups of colors since ordering starts making a difference. Image similarity can likewise be done by comparing color histograms, this approach does still not capture the number of colors or other qualities such as classifying according to type (Sequential, Diverging or Qualitative). My goal is to use expert knowledge to calculate features that can be used to calculates similarities

<b>Emil's presentation can be found at: https://github.com/ocrug/presentations/blob/master/2018-09-25_Color_talk/color-talk.pdf</b>

If you are interested in attending the DataScienceGo conference
https://www.datasciencego.com/

Use the following link and get 73% off the list price.
https://www.datasciencego.com/ocrug-special-discount