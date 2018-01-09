Last Modified: June 26, 2016
German Ros
gros@cvc.uab.es
htto://synthia-dataset.net

SYNTHIA: The SYNTHetic collection of Imagery and Annotations

This package contains the SYNTHIA-Rand subset as described in the paper:

German Ros, Laura Sellart, Joanna Materzynska, David Vazquez, Antonio M. Lopez; Conference on Computer Vision and Pattern Recognition (CVPR), 2016, pp. 3234-3243 
@InProceedings{Ros_2016_CVPR,
author = {Ros, German and Sellart, Laura and Materzynska, Joanna and Vazquez, David and Lopez, Antonio M.},
title = {The SYNTHIA Dataset: A Large Collection of Synthetic Images for Semantic Segmentation of Urban Scenes},
booktitle = {The IEEE Conference on Computer Vision and Pattern Recognition (CVPR)},
month = {June},
year = {2016}
}

DISCLAIMER: 
The data here presented was originally used to train the models of the CVPR paper and to perform an initial evaluation.
If you are looking for the full SYNTHIA dataset, it is *NOT* this one. This version is just an initial subset.


DESCRIPTION:

The package contains the following data,

* ALL.txt:  Text file listing all the images of the package (one per line)
* RGB: 	    folder containing standard 960x720 RGB images used for training
* GTTXT:    folder containing text files (one per image). Each text file contains 720x960 values
	    separated by spaces (720 rows and 960 columns), with class IDs from 0 to 11 (see below)
* GT:	    folder containing png files (one per image), with class represented as colors (see below)

class		color		R	G	B	ID
void		Black		0	0	0	0
Sky		Grey		128	128	128	1
Building	Red		128	0	0	2
Road		Pink		128	64	128	3
Sidewalk	Blue		0	0	192	4
Fence		Grey-purple	64	64	128	5
Vegetation	Dark yellow	128	128	0	6
Pole		Light yellow	192	192	128	7
Car		Purple		64	0	128	8
Sign		Salmon		192	128	128	9	
Pedestrian	Yellow-brown	64	64	0	10
Cyclist		Light blue	0	128	192	11
