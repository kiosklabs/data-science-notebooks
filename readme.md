![Python 2.7](https://img.shields.io/badge/python-2.7-blue.svg)
![Python 3.5](https://img.shields.io/badge/python-3.5-blue.svg)
![License](https://img.shields.io/badge/license-MIT%20License-blue.svg)

## Data Science Notebooks

This contains the ipython notebooks I've used for Udemy's Data Science and Machine Learning course.
I've been using these as a reference whenever I create submissions to Kaggle Competitions.

## Instructions

### Anaconda

Anaconda is a free distribution of the Python programming language for large-scale data processing, predictive analytics, and scientific computing that aims to simplify package management and deployment.

Follow instructions to install [Anaconda](https://docs.continuum.io/anaconda/install) or the more lightweight [miniconda](http://conda.pydata.org/miniconda.html).

### Module Dependencies

You can install the dependencies by running pip install on the requirements.txt file. Pls make sure that the pip command used is the one provided by anaconda. This can be verified by the 'which pip' command if you're on linux.

$ pip install -r requirements.txt

### running-notebooks

To view interactive content or to modify elements within the IPython notebooks, you must first clone or download the repository then run the ipython notebook.  More information on IPython Notebooks can be found [here.](http://ipython.org/notebook.html)

Assuming that anaconda and the module dependencies are installed, we can view our notebooks by running jupyter-notebook in the cloned directory.

1. Clone this repo: `git clone https://github.com/kiosklabs/data-science-notebooks.git`
2. Enter directory: `cd data-science-notebooks`
3. Run Jupyter: `jupyter-notebook`

After this, a new tab will open in your window that will display the jupyter notebook browser with the current folder set as home.
