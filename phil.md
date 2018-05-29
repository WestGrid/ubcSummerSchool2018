---
layout: default
title: Parallelization in Python 3 with large datasets
nav: false
---

**Instructor**: Philip Austin (Earth, Ocean and Atmospheric Sciences, UBC)

**Title**: Parallelization in Python 3 with large datasets

The objective is to learn how to write parallel Python programs that make use of multiple cores on a
single node. The tutorial will introduce several python modules that schedule operations and manage data
to simplify multiprocessing with Python.

**Target audience**: Researchers interested in Python programming on multiple core machines

**Course plan**:

1. Benchmarking parallel code
1. Understanding the global interpreter lock (GIL)
1. Multiprocessing and multithreading with joblib
1. Checkpointing/restarting multiprocessor jobs
1. Writing extensions that release the GIL:
   1.  Using numba
   1.  Using cython
   1.  Using C++ and pybind11
1. Using xarray to analyze out-of-core datasets
1. Using dask and xarray to compute on multiple cores
1. Visualizing parallelization with dask
1. Setting up a conda-forge environment for parallel computing

**Duration**: 3 hours

**Level**: intermediate

**Prerequisites**: Some familiarity with Jupyter notebooks, Python and numpy at the level of Jake
Vanderplas' [Whirlwind tour of Python](https://github.com/jakevdp/WhirlwindTourOfPython).


**Setup**:

- All the examples in the tutorial should work on Windows, MacOS or Linux laptops that have Miniconda 3.6 installed.

- *Python installation*: [https://clouds.eos.ubc.ca/~phil/courses/parallel_python/00_intro.html](https://clouds.eos.ubc.ca/~phil/courses/parallel_python/00_intro.html)

- *Course notes*: [https://clouds.eos.ubc.ca/~phil/courses/parallel_python/index.html](https://clouds.eos.ubc.ca/~phil/courses/parallel_python/index.html)

- *Course notebooks*:  (under construction) download from [https://github.com/phaustin/parallel_python_course](https://github.com/phaustin/parallel_python_course)


