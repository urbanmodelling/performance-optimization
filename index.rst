.. Openfoam Doc documentation master file, created by
   sphinx-quickstart on Wed May 24 15:31:55 2023.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


Performance Optimization using OpenFOAM testcases
=================================================
OpenFOAM is the *free, open source CFD software* developed primarily by OpenCFD Ltd since 2004. 
It has a large user base across most areas of engineering and science, from both commercial and academic organisations.
OpenFOAM has an extensive range of features to solve anything from complex fluid flows involving chemical reactions, 
turbulence and heat transfer, to acoustics, solid mechanics and electromagnetics.

Getting started
---------------

* :doc:`About</Contents/about>`
* :doc:`Installation</Contents/installation>`
* :doc:`Software</Contents/software>`

Software Components
===================
* :doc:`Paraview</Software/paraview>` is an open-source application for visualizing two- and three-dimensional data 
  sets. The size of the data sets ParaView can handle varies widely depending on the architecture on which the 
  application is run.The platforms supported by ParaView range from single-processor workstations to multiple-processor
  distributed-memory supercomputers or workstation clusters.

* :doc:`Valgrind</Software/valgrind>` Valgrind is an instrumentation framework for building dynamic analysis tools. 
  There are Valgrind tools that can automatically detect many memory management and threading bugs, and profile your
  programs in detail. You can also use Valgrind to build new tools.
  
* :doc:`VTune</Software/vtune>` is a popular performance profiling tool that targets both 32-bit and 64-bit x86 architectures.
  The tool collects profiling data during runtime
  and then, either through the command line or GUI, provides a variety of options for viewing and analyzing that data. 
  
* :doc:`Tau</Software/tau>` is a performance evaluation tool. It supports parallel profiling and tracing.Profiling and tracing can measure time as well as hardware performance counters.

.. .. note:: 
..    Version 1912

.. toctree::
   :maxdepth: 2   
   :hidden:
   :caption: GETTING STARTED:

   Contents/about
   Contents/installation
   Contents/software

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: SOFTWARE:

   Software/paraview
   Software/valgrind
   Software/vtune
   Software/tau

.. toctree::
   :maxdepth: 2
   :hidden:
   :caption: REFERENCES:

   References/ref1
 

.. Indices and tables
.. ==================

.. * :ref:`genindex`
.. * :ref:`modindex`
.. * :ref:`search`
