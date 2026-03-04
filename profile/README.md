# Codebase for the Sheffield Tobacco and Alcohol Policy Modelling

This GitHub organisation stores the R packages underlying the Sheffield Tobacco and Alcohol Policy Model (STAPM) and associated repositories of modelling projects, statistical analysis, and data processing. 

For more about STAPM visit the [Sheffield Addictions Research Group (SARG)
](https://sarg-sheffield.ac.uk/research/modelling/stapm/) website.

For open source code used to produce specific publications see our [open access repositories](https://github.com/STAPM)

## Overview
The aim of the STAPM research programme at the [Sheffield Centre for Health and Related Research](https://www.sheffield.ac.uk/scharr) at the University of Sheffield, UK, is to identify and evaluate approaches to reducing the harm from tobacco and alcohol, with the aim of improving commissioning in a public health policy context, i.e. providing knowledge to support benefits achieved by policymakers.

The two objectives of the STAPM research programme are:

- To evaluate the health and economic effects of past trends, policy changes or interventions that have affected alcohol consumption and/or tobacco smoking
- To appraise the health and economic outcomes of potential future trends, changes to alcohol and/or tobacco policy or new interventions

The STAPM platform is not linked to the tobacco or alcohol industry and is conducted without industry funding or influence.

## Code
The modelling was developed in R and R studio, with particular attention to utilising new developments in the software environment to organise, document, and version control code.   

A set of internal STAPM R packages have been developed that contain code used for particular purposes, e.g. to estimate smoking state transition probabilities from cross-sectional survey data (see https://stapm-platform.github.io/). Packaging up code into modular functions and packages makes the processes applied in modelling easier to document, adapt and reuse across projects.   

Some STAPM code is starting to become publicly available on this GitHub repository, but the majority is currently available only to the project team.  

## Code repositories

Below are links to various code repositories. This list is not exhaustive, but contains the R packages, core repositories containing the different models built on the STAPM platform, and key input data processing repositories that ensure consistency in data cleaning across projects and models.

### Tobacco and Alcohol Tax and Price Intervention Simulation Model (TAX-sim) 

- [TAX-sim](https://github.com/stapm-platform/TAX-sim) - the main development repo for the TAX-sim model. 
- [TAX-sim v2.7.0](https://github.com/stapm-platform/TAX-sim-v2.7.0) - the most recent release version of the TAX-sim model, currently 2.7.0. 


### The Sheffield Alcohol Policy Model in R (SAPM-R)

- [SAPM-R](https://github.com/stapm-platform/SAPM-R) - the main development repo for the SAPM-R model. 
- [SAPM-R v1.2.1](https://github.com/stapm-platform/SAPM-R-v1.2.1) - the most recent release version of the SAPM-R model, currently 1.2.1.

### R packages 

- [stapmr](https://github.com/stapm-platform/stapmr) - the main STAPM R package, containing the functions required to run the different models built on the platform.
- [pricepol](https://github.com/stapm-platform/pricepol) - the R package for modelling price and tax policy interventions in the TAX-sim model.
- [hseclean](https://github.com/stapm-platform/hseclean) - the R package for cleaning the main survey data sources containing alcohol and tobacco consumption data - the Health Survey for England, Scottish Health Survey, and National Survey for Wales.
