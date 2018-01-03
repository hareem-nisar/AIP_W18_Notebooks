# ECE 4438B SimpleITK Python Notebooks

As of this writing, SimpleITK version >=1.0.0 is required to run these notebooks. This version is available from [PyPi](https://pypi.python.org/pypi/SimpleITK) and [Source Forge](http://sourceforge.net/projects/simpleitk/files/SimpleITK/1.0.0/Python/).

## Setting Up a Python Environment

We recommend setting up a separate Python virtual environment to run through these notebooks as a tutorial.

## Anaconda
With [Anaconda](https://www.continuum.io/) you can set up a virtual environment, named sitkpy, and install all dependencies including SimpleITK using a single command:

    conda env create -f environment.yml



### Downloading Data

The data is automatically downloaded to the "Data" directory when you execute the notebooks.

Alternatively, to download all the data before hand:

    cd AIP_W18_Notebooks
    Utilities/downloaddata.py Data/ Data/manifest.json

### Run the notebooks

To launch:

    cd SimpleITK-Notebooks/Python
    ~/sitkpy/bin/jupyter notebook

### Working offline

In some situations, such as a tutorial session, you may not have internet access. This requires that you:

1. Download the data in advance - see above.
