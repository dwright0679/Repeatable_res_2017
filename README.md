cat(readLines("inputs/readme-header.txt"), sep = '\n')

---
title: "Repeatable Research"
date: "`r format(Sys.time(), '%d %B, %Y')`"
output: 
  github_document:
    toc: true
---

<!-- README.md is generated from README.Rmd. Please edit that file -->

```{r, echo = FALSE}
knitr::opts_chunk$set(
  collapse = TRUE,
  comment = "#>",
  fig.path = "readme-figs/"
)
```

# Repeatable_res_2017
repeatable research course repository

My goal for the course is to reproduce some analysis that was completed using software other than R, and create an R package
that is clear, well commented and easy to follow.  The ultimate output for the analysis should be two figures and one power
analysis.  A network analysis of coastal and central valley O. mykiss and a coorespondense analysis of population relationships.
If possible, I would like to perform a power analysis to determine if the SNP data has as much power to perform pop structure
analysis as microsat data.
