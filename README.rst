Welcome to SPLF 2003
====================

|build-devel| |docs|

**SPLF2003** is a Fortran 2003 library for B-Splines/NURBS and Computer Aided Design Algorithms. 

Requirements
************

- **cmake** (version 2.8 or higher)

- **Fortran** 2003 Compiler (gfortran version 4.7 or higher, or appropriate ifort)


Install
*******

We first install the Fortran library/headers using *cmake* (by default the installation path
is **$PWD/../usr**)::

  mkdir build && cd build
  cmake -DCMAKE_Fortran_FLAGS="-fPIC" ..
  make && make install && cd ..


.. More information
.. ^^^^^^^^^^^^^^^^
.. 
.. Compilers
.. _________
.. 
.. **SPL** was tested with the following compilers
.. 
.. * gcc: 4.7, 4.8.4, 4.8.5, 4.9.3, 5.4
.. * intel: 15.0.4, 16.0.3. mpiifort 4.1.3, 5.0, 5.1
.. * pgi

