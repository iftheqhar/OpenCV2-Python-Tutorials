.. _Install-OpenCV-Python-in-Fedora:

Install OpenCV-Python in Fedora
*********************************

Goals
======

In this tutorial, you will learn to setup OpenCV-Python in your Fedora system. Below steps are tested for Fedora 18.

Required Packages
==================
#. Python
#. Numpy
#. OpenCV

Below are some optional packages which will be useful in your journey.

#. Matplotlib
#. SciPy

Install Python, Numpy, Matplotlib, Scipy to their default locations. To install OpenCV, you can either use prebuilt binaries or compile from source.

Installing OpenCV from prebuilt binaries
=========================================
#. Install all packages with following command in terminal as root.

.. code-block:: bash

    yum install python-numpy opencv opencv-python
    
#. Open Python IDLE and type following codes in Python terminal.

    >>> import cv2
    >>> print cv2.__version__
    
If the results are printed out without any errors, congratulations !!! You have installed OpenCV-Python successfully.

Installing OpenCV from source 
===============================
#. Put complete compilation steps here
