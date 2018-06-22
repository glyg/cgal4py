======
README
======

This is a fork of Meagan Lang's @langmm `cgal4py` - original project can be found on [bitbucket](https://bitbucket.org/langmm/cgal4py/src/default/). I forked it to be able to compile and use it with python 3.6.

For the moment I stripped all the parallel code.

cgal4py is a Python interface for using the `CGAL <http://www.cgal.org>`__ Delaunay triangulation classes in any number of dimensions. Triangulation in parallel is also supported using the algorithm described in `Peterka, Morozov, & Phillips (2014) <http://mrzv.org/publications/distributed-delaunay/>`_. Documentation for cgal4py can be found `here <http://cgal4py.readthedocs.io/en/latest/>`_.

---------
Licensing
---------
cgal4py is released as open source software under a BSD license.

------------
Requirements
------------
For running in serial:

 * `Python 3.6 <https://www.python.org/download/releases/3.6/>`_
 * C++14 compiler
 * `Cython <http://cython.org/>`_
 * `CGAL <http://www.cgal.org/download.html>`__ Version 3.5 or higher is required for periodic triangulations in 3D and version 4.9 or higher is required for periodic triangulations in 2D.

For running in parallel you will need the above plus:

 * MPI (either `MPICH <https://www.mpich.org/>`_ or `OpenMPI <https://www.open-mpi.org/>`_)
 * `mpi4py <http://pythonhosted.org/mpi4py/>`_
 * `multiprocessing <https://docs.python.org/2/library/multiprocessing.html>`_
 * `cykdtree <https://github.com/cykdtree/cykdtree>`_

------------
Installation
------------

From Source
===========

TODO

-----------------
Who do I talk to?
-----------------
This package is currently maintained by `Meagan Lang <mailto:langmm.astro@gmail.com>`_.
This fork is maintained by `Guillaume Gay <mailto:guillaume@damcb.com>`_
