# Brain-regions-associated-with-happiness
This repository is created as part of the home assignment for "Programming for Psychologists" at the VU Amsterdam and portays the brain regions associated with happiness.

+ **Vivienne Kurth** (2867361)
+ **Date:** November 27th
+ **Neurosynth Happy Dataset:** https://neurosynth.org/analyses/terms/happy/

## Description of the Project
My home assignment visualizes fMRI data to explore brain regions associated with happiness, using the Neurosynth Happy Dataset to analyze and display activation patterns in on neuroanatomical brain scans. Besides, i created a histogram of the positive values in the functional data file to show the distribution of the data. Lastly, I was curious about the location of the highest activation in the brain when faced with the concept of happiness so I visualized it in the last step. 

## Table of Contents
**Data used**: Neurosynth Happy Dataset (https://neurosynth.org/analyses/terms/happy/)
+ anatomical.nii
+ happy_uniformity-test_z_FDR_0.01.nii
**Notebook**: visualizing_happy_fmridata.ipynb

## Python Packages Used
+ **os, glob and shutil** (file and directory management)
+ **nilearn** (for neuroimaging data visualization)
+ **nibabel** (for handling neuroimaging data formats)
+ **numpy** (for numerical operations)
+ **matplotlib** (for plotting)