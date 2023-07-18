{% include navigation.html %}

# [trex (**T**errestrial **R**angeland data **EX**traction)](https://github.com/landscape-data-commons/trex)

## Background

Publicly available ecological data are important for research and land management, but accessing them can be difficult. Some data repositories like the [Landscape Data Commons (LDC)](https://landscapedatacommons.org/) and the [Ecosystem Dynamics Interpretive Tool (EDIT)](https://edit.jornada.nmsu.edu/) have user-facing APIs that can be used to retrieve large numbers of records quickly and in an automated, repeatable way. This package contains functions to assist with retrieving data from the LDC and EDIT via their APIs by constructing the relevant API calls and downloading the data for the user.

## Installation

To install trex and all documentation, use:

`devtools::install_github("landscape-data-commons/trex", build_vignettes = TRUE)`