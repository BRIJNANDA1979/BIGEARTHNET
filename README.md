# BIGEARTHNET  
This project is based on open source Sentinel 2 satellite dataset.
It is a multi labelled dataset.
It has 46 types of classes.
Aim of this project is to train a model on these 46 classes.
Each image has 12 different bands.
Using custom created merge bands module, a stacked geotiff file is created.
These geotif files are then converted to numpy arrays.
A CNN model is trained on these geotif files.
