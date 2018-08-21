# CV_tutorial

##Anaconda install virtual env
or using virtual env

## Install virtualenv for python3 
pip3 install virtualenv

## Make a directory for virtual environments
mdkir ~/virtualenvs

## Make a virtual environment
virtualenv --system-site-packages -p python3 ~/virtualenvs/cv_course

## activate environment
source ~/virtualenvs/cv_course/bin/activate

## Install iPython
pip3 install ipython

## install Jupyter
pip3 install jupyter

## Install kernel
python3 -m ipykernel install --user --name cv_course --display-name "cv_course"

## Install libraries
pip3 install -r requirements.txt