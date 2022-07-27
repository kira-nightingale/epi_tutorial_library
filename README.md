README: epi\_tutorial\_library
================

## Project description

This repo contains a series of tutorials for quantitative epidemiologic
methods in R. The primary focus will be on characterizing and modeling
infectious disease.

## Table of Contents

*The repo is organized into folders by methodology.*

Summer2022Schedule

-   .Rmd file is source code and .html is rendered output.

-   Tentative schedule for topics to discuss. will be updated throughout
    the summer and populated with hyperlinks.
    [Here](https://rpubs.com/bhraynor/MethodsSummer2022) is the
    published web page.

**Spatial/**  
*A folder of sample codes to explore spatial data - both visualization
and analysis.*

01\_ChoroplethMaps

-   The .Rmd file is the R markdown code and the .html file is the
    rendered html output.

-   R code for a tutorial on spatial visualization and analysis
    primarily focused on choropleth maps.

-   Includes code to work with point,line, and polygon spatial data
    using the sf package.

-   This [tutorial](https://rpubs.com/bhraynor/MethodsSummer2022) runs
    through an example using freely accessible data on the city of
    Philadelphia looking at litter index and trashcan availability.

02\_Mapping

-   The .Rmd file is the R markdown code and the .html file is the
    rendered html output.

-   R code for making visually appealing maps using 3 methods: layering
    shapefiles, adding background tiles, creating interactive maps

-   This [tutorial](https://rpubs.com/bhraynor/mapping) runs through an
    example using freely accessible data on hospital locations in the
    city of Philadelphia.

03\_GPStracking

-   The .Rmd file is the R markdown code and the .html file is the
    rendered html output.

-   R code for estimating home range from GPS tracking data using KDE
    and t-locoh.

-   This [tutorial](https://rpubs.com/bhraynor/Tutorial3_GPStracking)
    runs through an example using the t-locoh and kde examples.

04\_SpatialClustering

-   The .Rmd file is the R markdown code and the .html file is the
    rendered html output.

-   R code for estimating spatial epi statistics including scan
    statistics for clustering, relative risk, and Moran’s I.

-   This [tutorial](https://rpubs.com/bhraynor/SpatialEpi) runs codes
    provided in package examples to execute these methods.

**TransmissionModels/**  
*A folder of sample codes for mathematical models of infectious disease
transmission.*

05\_MetapopulationModel

-   The .Rmd file is the R markdown code and the .html file is the
    rendered html output.

-   R code for a simple, deterministic, metapopulation model.

-   This [tutorial](https://rpubs.com/bhraynor/MetapopulationModel) runs
    through 2 examples look at systems with 3 patches coupled in
    different configurations.

06\_StochasticSIR

-   The .Rmd file is the R markdown code and the .html file is the
    rendered html output.

-   R code for a simple, stochastic SIR model.

-   This [tutorial](https://rpubs.com/bhraynor/StochasticSIR) runs
    through stochastic simulation code for a simple SIR model.

07\_MetapopulationModel

-   The .Rmd file is the R markdown code and the .html file is the
    rendered html output.

-   R code for metropolis hasting sampler to estimate parameters for
    simulated SIR data.

-   This [tutorial](https://rpubs.com/bhraynor/SIRinference) corresponds
    to the code.

SIR\_schematic.png

-   Simple flow chart schematic of SIR metapopulation system used in
    05\_MetapopulationModel code.

System1.png

-   Simple flow chart schematic of 3 patches interacting used in
    05\_MetapopulationModel code.

System2.png

-   Simple flow chart schematic of 3 patches interacting used in
    05\_MetapopulationModel code.

## How to use

To use these codes, clone the repo and run the codes.

## Contact information

Brinkley Raynor  
<bhraynor@gmail.com>
