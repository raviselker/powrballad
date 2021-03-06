
[![codecov](https://codecov.io/gh/Reoke/powrballad/branch/master/graph/badge.svg)](https://codecov.io/gh/Reoke/powrballad) [![CRAN\_Status\_Badge](http://www.r-pkg.org/badges/version/powRballad)](https://cran.r-project.org/package=powRballad) [![license](https://img.shields.io/github/license/mashape/apistatus.svg)](http://choosealicense.com/licenses/mit/) [![Build Status](https://travis-ci.org/Reoke/powrballad.svg?branch=master)](https://travis-ci.org/Reoke/powrballad) [![Project Status: Concept – Minimal or no implementation has been done yet, or the repository is only intended to be a limited example, demo, or proof-of-concept.](http://www.repostatus.org/badges/latest/concept.svg)](http://www.repostatus.org/#concept)

Introducing the powRballad package
----------------------------------

This package solves the most fundamental problem we all have when we walk into a kareokebar after UseR;

> what song to pick?

The powRballad package helps you in selecting the most optimal song based on you R-skill and Nationality.

It has one function: `select_powerballad()`

How to install
--------------

If you don' have devtools installed: 'install.packages('devtools')'

Install from github with

    library(devtools)
    install_github('reoke/powrballad')

adding to this package
----------------------

If you feel like we missed a critical powerballad or misspelled something (likely) add it to the textfile which can be found in [inst/extdata/powerballads.txt](inst/extdata/powerballads.txt) if you add more then one song, add yourself to the description file as well. use this format:

`person("firstname","lastname", role = "ctb")` *ctb means contributor*
