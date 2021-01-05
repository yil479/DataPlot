# Data plot
This repo is for plotting tdt tanks(signals for channels and deltaF for each tanks)

## Directories and files
Go to https://drive.google.com/drive/folders/1x_4U6RisY2-JCa5_f7mMl_0bsPqcjNQA?usp=sharing and download the __new_data__ folder

Place the folder into this folder so that the folder structure looks like below

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

### Part1: Install packages(only need to run this section once )

Run these cells one by one and wait until each package is installed successfully,there should be success message:

!pip install matplotlib\
!pip install numpy\
!pip install tdt

### Part2: Prepare packages and read data for plot preparation

This section is to import all the installed packages and then read all the data from the new_data folder\
I also checked the data channel types at the end of the section(make sure to do this step before plotting so that it's clear what channel we are looking at)

### PART3: Plot signals from two channels of each tank then plot the deltaF for each channel(ignore white noise)

I wrote a more detailed explation for the code plotting the first tank since the rest of them are essentially the same.\
There are 7 tanks in total and 14 plots for A and B channels. DeltaF plots are only generated if the signals are not white noise.
