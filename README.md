---
title: "A gRadual Introduction to Bioconductor"
output: rmarkdown::html_vignette
vignette: >
  %\VignetteIndexEntry{An Example Workshop}
  %\VignetteEngine{knitr::rmarkdown}
  %\VignetteEncoding{UTF-8}
---

# A gRadual Introduction to Bioconductor

Authors:
    Jenny Drnevich^[University of Illinois],
    Ted Laderas^[Another Institution].
    <br/>
Last modified: 28, July 2026.

## Overview

### Description

This workshop gives a quick overview of the Bioconductor project, particularly the shared infrastructure that facilitates inter-operability between Bioconductor packages. The hands-on part will explore one of the most commonly-used S4 objects, a SummarizedExperiment. We will review it's structure, how to manipulate it and make figures, and how to construct one from your own data. Finally, we will briefly explore the Bioconductor package repository and learn how to install Bioconductor on your own computer.


### Pre-requisites

List any workshop prerequisites, for example:

* Basic knowledge of R syntax
* Basic knowledge of `data.frame`s and how to manipulate them using the `tidyverse`.
* Basic knowledge of Bulk RNA Sequencing (that is, you know what a count matrix is) and Experimental Design

### Participation

Students will have access to a instance of RStudio / Bioconductor with runnable RMarkdown files on https://orchestraplatform.com 

### _R_ / _Bioconductor_ packages used

- `SummarizedExperiment`
- `tidySummarizedExperiment`
- `DESeq2`

### Time outline

The workshop will be held in-person at Fred Hutch Cancer Center on August 10:

| Activity                     | Time |
|------------------------------|------|
| Exploring Bioconductor Objects | 60m  |
| Loading Data into Objects      | 15m  |
| Installing Bioconductor and Getting Help | 15m |


### Learning goals

* **Explore** and **contrast** how Bioconductor objects differ from `data.frames`
* **Load** your own expression count matrix and experimental metadata into an Bioconductor object.
* **Install** Bioconductor packages and find packages and help documentation.

## Workshop

Start with

- [Introduction to Bioconductor Objects](articles/intro.html)
- [Loading Data into Bioconductor Objects](articles/loading-data.Rmd)
- [Installing Bioconductor and Finding Help](articles/installing.Rmd)


