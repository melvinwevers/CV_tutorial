# Computer Vision Tutorial
### Thomas Smits & Melvin Wevers

Welcome to this workshop on Computer Vision and Convolutional Neural Networks. In a couple of steps we explain how computer vision techniques can be used to manipulate and analyse images and how convolutional neural networks (using KERAS) use transformations to analyse visual material.

## Installation instructions

### Install using Anaconda

The easiest way to install the requires libraries is through Anaconda. Make sure you have anaconda 5.2.0 installed for python 3.6. 

You can download anaconda 5.2.0 here: https://repo.anaconda.com/archive/

Or you can make a python 3.6. environment in anaconda. This is described here: http://docs.anaconda.com/anaconda/faq/#how-do-i-get-anaconda-with-python-3-5-or-3-6


Clone this repository to your local machine using

`git clone https://github.com/melvinwevers/CV_tutorial.git`

Navigate to this directory and then input (replace new_environment with your preferred name for this environment, for example CV_course

`conda create -n new_environment --file req.txt` 

If this does not work you can also create a new environment in the Anaconda GUI and install the following libraries by hand:

* pandas
* os
* Matplotlib
* skimage
* keras
* scipy
* glob
* tqdm
* sklearn
* face_recognition

Activate the environment in Anaconda or using your terminal (again replace new_environment with the name given to your environment)

`conda activate new_environment`

### Install using virtualenv for python3 
These instructions are for mac os. 
For windows please see these instructions: https://programwithus.com/learn-to-code/Pip-and-virtualenv-on-Windows/

Install virtualenv

`pip3 install virtualenv`

make directory for virtual environments (feel free to change this)

`mkdir ~/virtualenvs`

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
