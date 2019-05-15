# SupAgro Modelling Course 2019

Material for the SupAgro Modelling Course

## Install

### Conda Installation

[Conda](https://conda.io) is a package manager that can be installed on Linux, Windows, and Mac.
If you have not yet installed conda on your computer, follow these instructions:

[Conda Installation](https://conda.io/docs/user-guide/install/index.html). Follow instructions for Miniconda.

[Conda Download](https://conda.io/miniconda.html). Use the Python 2.7 based installation.

#### Windows, Linux, Mac

Create an environment named *openalea*:
Launch a console (See Anaconda Prompt in Start menu on windows)
    
    conda create -n openalea -c openalea openalea.plantgl openalea.lpy openalea.mtg alinea.caribu boost=1.66 

Activate the *openalea* environment:

    conda activate openalea

source should be written only on linux and macos.
Install the different packages

    conda install notebook=5.4 matplotlib pandas nbformat git

    conda install -c openalea -c conda-forge pvlib-python alinea.astk


## Installation of R & co

You can install everything by yourself, or using the r channel in conda.

With **conda**:

### Install RStudio, Rmarkdown


    [source] deactivate
    conda create -n renv -c r rstudio r-rmarkdown r-car r-lme4
    
    [source] activate renv
    

### Install R packages
* PerformanceAnalytics
* lme4
* car
* agricolae
* sensitivity
* lhs
* planor

Under **R**, you can install everything using:
    
    install.packages(c('PerformanceAnalytics','agricolae','sensitivity','lhs','planor') )
