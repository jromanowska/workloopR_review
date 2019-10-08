---
output: github_document
---


# `workloopR` - package review repository

##

This repo contains files associated with the **rOpenSci** review of

### **`workloopR`: ropensci/software-review**  issue [\#NA](https://github.com/ropensci/onboarding/issues/).

<br>


***

## **Reviewer:** [\@jromanowska](https://github.com/jromanowska)
### Review Submitted:
**`r cat(sprintf("**Last updated:** %s", Sys.Date()))`**

<br>

### see the review report [here:](https://jromanowska.github.io/workloopR-review/index.nb.html)

or view the submitted review to rOpenSci [here:](https://github.com/jromanowska/workloopR-review/blob/master/pkgreview.md)

<br>


## Package info

**Description:**

Functions for the import, transformation, and analysis of data from muscle physiology experiments. The work loop technique is used to evaluate the mechanical work and power output of muscle. Josephson (1985) <https://jeb.biologists.org/content/114/1/493> modernized the technique for application in comparative biomechanics. Although our initial motivation was to provide functions to analyze work loop experiment data, as we developed the package we incorporated the ability to analyze data from experiments that are often complementary to work loops. There are currently three supported experiment types: work loops, simple twitches, and tetanus trials. Data can be imported directly from .ddf files or via an object constructor function. Through either method, data can then be cleaned or transformed via methods typically used in studies of muscle physiology. Data can then be analyzed to determine the timing and magnitude of force development and relaxation (for isometric trials) or the magnitude of work, net power, and instantaneous power among other things (for work loops). Although we do not provide plotting functions, all resultant objects are designed to be friendly to visualization via either base-R plotting or 'tidyverse' functions.

**Author:** `r c(
    person("Vikram B.", "Baliga",
        email = "vbaliga87@gmail.com",
        role = c("cre", "aut"),
        comment = c(ORCID = "0000-0002-9367-8974")),
    person("Shreeram", "Senthivasan",
        email = "shreeramsenthi@gmail.com",
        role = "aut",
        comment = c(ORCID = "0000-0002-7118-9547")))`

**repo url:** <https://github.com/vbaliga/workloopR>

**website url:** <https://vbaliga.github.io/workloopR/>
