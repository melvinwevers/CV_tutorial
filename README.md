# Computer Vision Tutorial
### Thomas Smits & Melvin Wevers

Welcome to this workshop on Computer Vision and Convolutional Neural Networks. In a couple of steps we explain how computer vision techniques can be used to manipulate and analyse images and how convolutional neural networks (using KERAS) use transformations to analyse visual material.

### To do
- Improve classifier
- Remove output in notebook

## Installation instructions

### Install using Anaconda

The easiest way to install the requires libraries is through Anaconda. Make sure you have anaconda installed for python 3.6. 

Clone this repository to your local machine using

`git clone https://github.com/melvinwevers/CV_tutorial.git`

Navigate to this directory and then input (replace new_environment with your preferred name for this environment, for example CV_course

`conda create -n new_environment --file req.txt` 

Activate the environment in Anaconda or using your terminal (again replace new_environment with the name given to your environment)

`conda activate new_environment`

### Install virtualenv for python3 

Install virtualenv

`pip3 install virtualenv`

make directory for virtual environments (feel free to change this)

`mdkir ~/virtualenvs`

Make a virtual environment

`virtualenv --system-site-packages -p python3 ~/virtualenvs/cv_course`

activate environment

`source ~/virtualenvs/cv_course/bin/activate`

install iPython

`pip3 install ipython`

install Jupyter

`pip3 install jupyter`

install kernel

`python3 -m ipykernel install --user --name cv_course --display-name "cv_course"`

install libraries

`pip3 install -r requirements.txt`
