==================
Install directions
==================

This section covers the basics of how to download and install TomoPy.

.. contents:: Contents:
   :local:

Installing from Conda/Binstar
=============================

First you must have `Conda <http://continuum.io/downloads>`_ 
installed, then open a terminal or a command prompt window and run::

    conda install -c dgursoy tomopy


Updating the installation
=========================

TomoPy is an active project, so we suggest you update your installation 
frequently. To update the installation run in your terminal::

    conda update -c dgursoy tomopy

For some more information about using Conda, please refer to the 
`docs <http://conda.pydata.org/docs>`__.
    

Windows installation
====================

Anaconda packages are not available for Windows but you can install
tomopy for Python 2.7 following these steps:

1. Install the Python package `pywavelets`,
   for example using this command:
    pip install -U pywavelets
2. From The FFTW3 `ftp ftp://ftp.fftw.org/pub/fftw/`_ download the
   `FFTW3 library DLL for windows 64 bits: ftp://ftp.fftw.org/pub/fftw/fftw-3.3.4-dll64.zip`_
3. Unzip the contents of the FFTW zip into the root directory of your
   Python (for example ``C:\Anaconda`` if you are using Anaconda.
4. Get the egg package from the APS Jenkins build server
   (https://jenkins.aps.anl.gov/view/Python/job/Tomopy_trunk/ws/dist/),
   for example for version 0.1.11:
   https://jenkins.aps.anl.gov/view/Python/job/Tomopy_trunk/ws/dist/tomopy-0.1.11-py2.7-win-amd64.egg
5. Open a command prompt where the tomopy egg package is saved and run this
   command:
    easy_install tomopy-0.0.3-py2.7-win-amd64.egg
