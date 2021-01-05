# Data plot
This repo is for plotting tdt tanks(signals for channels and deltaF for each tanks)

## Directories and files

Please install the packages from the first section of the notebook

!pip install matplotlib\
!pip install numpy\
!pip install tdt

Below is the folder structure when running the jupyter notebook

    .
    ├── Final.ipynb
    ├── new_data                  
    │   ├── Algernon-200625-150526         
    │   ├── Algernon-200625-154539                 
    │   ├── Algernon-200625-162128
    │   ├── Algernon-200625-165959
    │   ├── Algernon-200810-151843
    │   ├── Algernon-200810-151923
    │   └── Algernon-200810-160610                   
    └── newtankPlots

Jupyter Notebook __Final.ipynb__ is the code for plotting\
Folder __new_data__ contains ALL the data tank files\
Folder __newtankPlots__ contains ALL the plot images generated from all tank files


## There are three parts of the jupternote book

Part1: Install packages(only need to run this section once )\

Part2: Prepare packages and read data for plot preparation\

PART3: Plot signals from two channels of each tank then plot the deltaF for each channel(ignore white noise)

