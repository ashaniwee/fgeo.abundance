
<!-- README.md is generated from README.Rmd. Please edit that file -->
forestr
=======

The goal of **forestr** is to provide tools for the analysis of forest dynamics.

Functions Index
---------------

-   [Go to index](https://forestgeo.github.io/forestr/reference/index.html)

Tutorials
---------

Calculations within a single census:

-   [Abundance and basal area](https://bookdown.org/forestgeoguest/abundance/)

Calculations between two censuses:

-   [Demography](https://bookdown.org/forestgeoguest/demography/)

Maps:

-   [Species distribution](https://bookdown.org/forestgeoguest/map/)

Installation
------------

Install forestr from ForestGEO's private GitHub repo.

    # To install from a private repo, use auth_token # with a token from
    # https://github.com/settings/tokens. You only need the repo # scope.

    # install.packages("devtools")

    # Install the master branch
    devtools::install_github("forestgeo/forestr", auth_token = "abc")

    # Install an ISSUE-specific branch with
    devtools::install_github("forestgeo/forestr@ISSUE", auth_token = "abc")

    # Then, load each time before using
    library(forestr)
