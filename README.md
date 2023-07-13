# Materials for CoDaS-HEP 2023 Columnar Data Analysis Tutorial

This repository contains the lecture notebooks and workbook used for [columnar data analysis](https://indico.cern.ch/event/1151367/timetable/#41-columnar-data-analysis), presented at CoDaS-HEP at 13:30pm on July 20, 2023 by Jim Pivarski and Ioana Ifrim.


## How to participate 


You don't need to install anything on your computer to participate; You can run the turorial notebook in your browser with JupyterLite:

https://ioanaif.github.io/columnar-data-analysis-codas-hep-2023/lab/index.html


### Running the notebooks on your personal computer

If you want to install and run the notebooks on your computer (including the lecture notebooks), you can do so by following these steps:


#### 1. Clone the repository

First clone this repository to your local machine via:

```
[TODO] insert link 
```

#### 2. Download conda (if you haven't already)

If you do not already have the conda package manager installed, please follow the instructions [here](https://docs.conda.io/en/latest/miniconda.html).



#### 3. Create a conda environment

Navigate to the  ``columnar-data-analysis-codas-hep-2023`` directory and create a new conda environment with the required
packages via:

```terminal
cd columnar-data-analysis-codas-hep-2023
conda env create --file environment.yml
```

This will create a new conda environment named "columnar-data-analysis-codas-hep-2023".

#### 4. Activate the environment

Next, activate the environment:

```
conda activate columnar-data-analysis-codas-hep-2023
```

#### 5. Launch JupyterLab

Finally, launch JupyterLab with:

```
jupyter lab
```
