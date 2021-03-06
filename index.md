---
title       : Interactive Documents with R
author      : Ramnath Vaidyanathan
framework   : minimal
highlighter : prettify
hitheme     : twitter-bootstrap
mode        : selfcontained
github      : {user: ramnathv, repo: user2014-idocs-slides, branch: gh-pages}
biglogo     : "slidify_logo_big.png"
---

# Interactive Documents with R

<a href="http://prose.io/#ramnathv/user2014-idocs-slides/edit/gh-pages/index.Rmd" class="button icon edit">Edit Page</a>



This repository consists of slides for my tutorial on Interactive Documents with R at UseR2014. Please download the repo as a zip file using the links in the sidebar.

## Installation

Slidify is not on CRAN and needs to be installed from `github` using the `devtools` package.

```S
pkgs <- c("slidify", "slidifyLibraries", "rCharts")
devtools::install_github(pkgs, "ramnathv")
```

While the installation process from `github` is relatively painless for Mac/Linux/Ubuntu users, it can make Windows users jump through hoops. For those of you on Windows that hit a bottleneck, here is an [excellent blog post](http://thiagosilva.wordpress.com/2013/02/17/installing-slidify-on-a-windows-machine/) that takes you through an alternate installation process that has been reported to work well.

## Tutorials

1. [Interactive Documents](tutorials/00)
1. [Slidify](tutorials/01)
2. [Frameworks](tutorials/02)
3. [Layouts](tutorials/03)
4. [Widgets](tutorials/04)
5. [How Slidify Works](tutorials/05)

<style>ol.linenums {margin-left: -5px;}</style>

<!-- rmarkdown v1 -->
