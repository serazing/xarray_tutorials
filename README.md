Tutorials for xarray
====================

This repository stores useful tutorials to perform computation in oceanography with dask_ and xarray_.

Dask_ provides parallel computation on multi-dimensional arrays using a task scheduler. Xarray_ provides a flexible use of the netCDF files as it has a similar in-memory representation for the data. Xarray_ also relies on pandas_ and benefits from the timeseries and groupby operation implemented in pandas_. All the

Installation
------------

The recommended way to install to install the requirements of these tutorials is to use conda_ to manage properly a python environment. 

After having cloned this repository, the package required for the tutorials may be installed using the following command::

conda env create -f xarray_env.yml

Then, activate the environement using::

source activate xarray_env

and finallly launch a jupyter notebook using the command::

jupyter notebook

Contents
--------
 * Computation of climatological quanitities



.. _dask: http://dask.pydata.org
.. _xarray: http://xarray.pydata.org
.. _conda: https://conda.io/
.. _pandas: http://pandas.pydata.org/
