# Labelling script for Napari package 

This labeling script reads in an existing csv from a by Deeplabcut analysed video and lets you add predefined labels in addition to the machine labels. 
Machine labels can be edited (move/remove). Theres also the functionality to make annotations at certain frames. 

Attention: Since there's no option yet to read in an annotated csv a video has to be finished before ultimately saving and closing it since there's no option to start from where you saved and closed it. 

## Installation 

- clone repository 
- cd /d "local path to repo folder" 
- conda env create -f environment.yml
- run jupyter through your preferred IDE/Online with environment 

## Short keys 
- Key "Down": Advance label 
- Key "Up": Decrement label 
- Key "left": Frame back 
- Key "Right": Frame forward 
- Key "Ctrl + Right": Annotate right step 
- Key "Ctrl + Left": Annotate right step
- Key "Ctrl + d": Saves all points as ...annnotated.csv 

## To DO 

- add option to read in annotated csv to pick up from where you left 
- create python standalone script from ipynb 
- make file paths universal 

## License

Based on: https://napari.org/dev/tutorials/annotation/annotate_points.html

[MIT](https://choosealicense.com/licenses/mit/)