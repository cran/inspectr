<!-- README.md is generated from README.Rmd. Please edit that file -->
inspectr
========

### A package for performing fidelity checks on messy dataframes.

[![Travis-CI Build Status](https://travis-ci.org/jenitivecase/inspectr.svg?branch=master)](https://travis-ci.org/jenitivecase/inspectr)

Inspectr consists of functions adapted from a quality control script I developed for performing data checks on large datasets from an educational assessment, then generalized for more generic application.

The inspectr package contains two classes of functions: column checks and basic fidelity checks. Column check functions allow the user to check data for fidelity without having to master apply functions, and basic fidelity check functions can be used to facilitate some common checks. The user can also define their own checks to use with the column check functions, making the package generalizable to unique data requirements.

#### Getting started

The data-checks vignette included with this package provides an overview of how to use the column check functions and illustrates the included basic fidelity check functions: `vignette("introduction", package = "dplyr")`
