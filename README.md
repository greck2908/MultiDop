# MultiDop README

<b>Note: MultiDop has been superseded by PyDDA (https://github.com/openradar/PyDDA). It is recommended that you install and use PyDDA rather than MultiDop.</b>

MultiDop is a Python-based interface between the C-based DDA code developed at
University of Oklahoma and the Python Atmospheric Radiation Measurement
Radar Toolkit (Py-ART) software developed at Argonne National Lab. Use this
software to perform 3D wind analyses using 2-3 independent Doppler radars.

To install:
1. Edit the Makefile in the src/ directory to match the compiler and path
   information relevant to your system.
2. “python setup.py install” in the master directory.

The installation will compile the DDA binary, which is the analysis engine, as
well as install the overall Python package. To see how to run the software,
view the example Jupyter notebook in the examples/ directory.

MultiDop has been tested using Python 2.7 and Python 3.6.

A conference presentation describing MultiDop and how to use it can be found at https://ams.confex.com/ams/97Annual/webprogram/Paper306647.html

Get Py-ART here: http://arm-doe.github.io/pyart/

MultiDop also requires numpy and xarray.
Get xarray here: http://xarray.pydata.org/en/stable/

Original C code developed by Corey Potvin (OU/CIMMS) and Alan Shapiro (OU). Subsequent major C code improvements and real-data functionality added by Daniel Betten (OU) and Gordon Carrie (OU).

Python code and C code modifications to ingest Py-ART grids were done by Timothy Lang (timothy.j.lang@nasa.gov).  

> If you use this software to produce an analysis for a presentation or
publication, you *must* cite the following papers:
http://journals.ametsoc.org/doi/abs/10.1175/2009JTECHA1256.1
(Shapiro et al. 2009, JTECH)
http://journals.ametsoc.org/doi/abs/10.1175/JTECH-D-11-00019.1
(Potvin et al. 2012, JTECH)

Latest release info:
[![DOI](https://zenodo.org/badge/84335317.svg)](https://zenodo.org/badge/latestdoi/84335317)
