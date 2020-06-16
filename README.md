# BIDS_tutorial
OHBM Brainhack 2020 Asia Pacific Hub BIDS Traintrack

This repository contains the BIDS Traintrack materials (lecture slides, example data and python code).

## Step 1: Make a local copy of the repository on your computer
You can either:
1. clone the repository using the git client on your computer (if you have installed it) or 
2. simply download the whole repository. 
In any case, please make use of the green 'Clone/Download' button in the upper right corner.
Please note the path where you have installed the repository, e.g., /home/draran/BIDS_tutorial

## Step 2: Create conda environment
Windows users: open conda prompt (suggest run as admin).  
MacOS/Linux users: open terminal application.

Navigate to the repository you have just cloned/downloaded:  
```sh
cd <PATH>
```
Create the new conda environment
```sh
conda env create -f 00_Scripts/bidsenv.yml
```
Activate the environment
```sh
activate bidsenv
```
## Step 3: Launch jupyter 
```
jupyter notebook 00_Scripts/BIDS_demo.ipynb
```
This command should open the BIDS demo notebook that we will use in the tutorial.
## Step 4: Wrap up
After you have finished with the demo, go back to terminal/prompt window.  
Type CTRL+C to stop the jupyter kernel.  
__All done!__