---
layout: post
title: "colourpycker / colourpickr"
subtitle: "Open-source packages for extracting colour codes from image files for use in data visualization projects"
image: "/images/colourpycker/donut.png"
---
## Code Repositories
- [Python](https://github.com/UBC-MDS/colourpycker)
- [R](https://github.com/UBC-MDS/colourpickr)

## Technique Overview
- Python
    - altair
    - pandas
    - matplotlib
    - cookiecutter
- R
    - ggplot
    - roxygen2
    - vignette
- Data Visualization
- Package Building
    - QA Testing (Code Coverage)
    - CI/CD
    - Versioning

## Walkthrough

![Demo](https://lzung.github.io/images/colourpycker/colourpycker_demo.mov)

You can find examples [here](https://ubc-mds.github.io/colourpickr/articles/colourpickr-vignette.html) and [here](https://github.com/UBC-MDS/colourpycker/blob/main/docs/example.ipynb).

## Overview
`colourpycker` and `colourpickr` are Python and R packages that can be used to extract colours from images for use in data visualization projects.  

These packages allow users to integrate unique colour palettes into their graphs for exploratory data analysis. The colours are retrieved from image data (via URL) and are selected based on their overall prominence in a picture. While there are existing tools that are used to process images and create figures independently, we aim to combine both of their functionalities to help programmers easily design effective and creative visualizations.
