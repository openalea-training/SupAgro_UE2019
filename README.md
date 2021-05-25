# SupAgro Modelling Course 2021

Material for the SupAgro Modelling Course

## Install

### Conda Installation

[Conda](https://docs.conda.io) is a package manager that can be installed on Linux, Windows, and Mac.
If you have not yet installed conda on your computer, follow these instructions:

[Conda Installation](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). Follow instructions for Miniconda.

[Conda Download](https://docs.conda.io/en/latest/miniconda.html). Use the Python 3.8 based installation.

#### Windows, Linux, Mac

Create an environment named *openalea*:
Launch a console (See Anaconda Prompt in Start menu on windows)
    
    conda create -n training -c fredboudon -c conda-forge openalea.plantgl openalea.lpy alinea.caribu alinea.astk python=3.8 

Activate the *openalea* environment:

    conda activate training
    pip install matplotlib pandas

