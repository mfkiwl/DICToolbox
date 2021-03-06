.. DICToolbox documentation master file, created by
   sphinx-quickstart on Tue Nov 20 10:23:06 2018.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to DIC Toolbox's documentation!
========================================

DIC Toolbox is a python tools created to work on 2D strain field map. 

It can import output from DICe and 7D. Other import function can be writen.

It is an open source code under GPL-v3. There is no guarantee if you are using it. It has been tested with python 3.9


.. toctree::
   :maxdepth: 1
   :caption: Documentation:


Installation
============

If you want just to use the toolbox without doing any devellopement

We advised to create a new python environement using conda :

.. code:: bash
    
    conda create --name envDIC python=3.9
    conda activate envDIC
    

You can clone the repository :
  
.. code:: bash

    git clone https://github.com/ThomasChauve/DICToolbox
    cd DICToolbox/
    
    
After you can install the requirements using pip :

.. code:: bash

    pip install -r requirements.txt
    
And finally install the DICToolbox package

.. code:: bash

	pip install .

.. code:: bash

    git clone https://github.com/ThomasChauve/DICToolbox
    cd DICToolbox/
    pip install .

Then you will find all the package in python using

.. code:: python

    import DICToolbox

Uninstall
*********

.. code:: bash
    
    pip uninstall DICToolbox


.. toctree::
    :maxdepth: 1
    :numbered:
    :caption: Documentation

    Documentation/Documentation
    CLASS/dic

.. toctree::
    :maxdepth: 1
    :numbered:
    :caption: CLASS

    CLASS/image2d
    CLASS/sTM
    CLASS/utils


Contact
=======
:Author: Thomas Chauve
:Contact: thomas.chauve@univ-grenoble-alpes.fr

:organization: UiO
:status: This is a "work in progress"
:version: 2.0



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
