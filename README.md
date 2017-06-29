
<!-- README.md is generated from README.Rmd. Please edit that file -->
Visibility / Fog Detection
==========================

[![Travis-CI Build Status](https://travis-ci.org/KNMI/visDec.svg?branch=master)](https://travis-ci.org/KNMI/visDec) [![AppVeyor Build Status](https://ci.appveyor.com/api/projects/status/github/KNMI/visDec?branch=master&svg=true)](https://ci.appveyor.com/project/KNMI/visDec) [![Coverage Status](https://img.shields.io/codecov/c/github/KNMI/visDec/master.svg)](https://codecov.io/github/KNMI/visDec?branch=master) [![Gitter](https://badges.gitter.im/KNMI/visDec.svg)](https://gitter.im/KNMI/visDec?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge)

Extract features from images for the purpose of fog detection / visibility estimation. The package can be installed via

``` r
devtools::install_github("KNMI/visdec")
```

The image processing is done via the package [imager](https://cran.r-project.org/web/packages/imager/index.html), which is a port to [cimg](http://cimg.eu/).
