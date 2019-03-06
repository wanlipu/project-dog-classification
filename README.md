# project-dog-classification
In this project, I will build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

Along with exploring state-of-the-art CNN models for classification and localization, I will also make design decisions about the user experience for my app. 

# Dependencies

## Configure and Manage Project Environment with Anaconda

Per the Anaconda [docs](http://conda.pydata.org/docs):

> Conda is an open source package management system and environment management system 
for installing multiple versions of software packages and their dependencies and 
switching easily between them. It works on Linux, OS X and Windows, and was created 
for Python programs but can package and distribute any software.

## Overview
Using Anaconda consists of the following:

1. Install [`miniconda`](http://conda.pydata.org/miniconda.html) on your computer, by selecting the latest Python version for your operating system. If you already have `conda` or `miniconda` installed, you should be able to skip this step and move on to step 2. You can also find achived miniconda version in this [`link`](https://repo.continuum.io/miniconda/), I used Miniconda3-4.5.1-Windows-x86_64 (python 3.6.5)
2. Create and activate * a new `conda` [environment](http://conda.pydata.org/docs/using/envs.html).

- __Windows__: 
```
conda create --name deep-learning python=3.6.5
conda activate deep-learning
conda install numpy matplotlib pandas jupyter notebook
conda install pytorch torchvision cudatoolkit=9.0 -c pytorch

```
