# **Predictors of grantsmanship and funding success for U.S. researchers**
This repository contains the R scripts to curate, validate, and generate the final model and visualization from the raw data collected via a nationwide survey on Proposal Deadlines.

## Getting Started

#### Prerequisites
- R and RStudio
- Required packages

#### Installing R Packages
Packages are available on CRAN and can be installed using a simple call to `install.packages()`:

    install.packages('PackageName')
	
	
## Script Set
##### Please run the following scripts sequentially
**Data Curation (dc)** 

- 1-dc-data -curate-and-processing.rmd
- 2-dc-process-phychometrics.rmd
- 3-dc-keydata-processing.rmd
- 4-dc-corequestions-processing.rmd

**Validation Scripts (vs)**
 - 5-vs-descriptive-statistics.rmd
 - 6-vs-model-grantsmanship.Rmd
 - 7-vs-model-grant-funding.rmd
