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
	- Curate the raw data from readcap and generate processed data file named AllData.csv
- 2-dc-process-phychometrics.rmd
 	- Process the phychometrics data and create the finals scores
- 3-dc-corequestions-processing.rmd
	- Process the core questions related to proposal deadlines
- 4-dc-keydata-processing.rmd
	- Transforms the data for the final model

**Validation Scripts (vs)**
 - 5-vs-descriptive-statistics.rmd
 	- Generates the descriptive statistics plot from the data
 - 6-vs-model-grantsmanship.Rmd
 	- Produce the grantsmanship models and the visualization
 - 7-vs-model-grant-funding.rmd
  	- Produce the grant funding and the combinrd grantsmanship+grant funding models and the visualization
