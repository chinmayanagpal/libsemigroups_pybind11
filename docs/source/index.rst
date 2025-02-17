libsemigroups_pybind11 - Version 0.1.6
======================================

python bindings for the C++ library libsemigroups
-------------------------------------------------

What is ``libsemigroups``?
~~~~~~~~~~~~~~~~~~~~~~~~~~

``libsemigroups``  is a C++14 library containing implementations of several
algorithms for computing finite and finitely presented semigroups. 
Namely:

- the `Froidure-Pin algorithm`_ for computing finite semigroups
- the `Todd-Coxeter algorithm`_ for finitely presented semigroups and monoids;
- the `Knuth-Bendix algorithm`_ for finitely presented semigroups and monoids;
- the `Schreier-Sims algorithm`_ for permutation groups;
- a preliminary implementation of the `Konieczny`_ and
  `Lallement-McFadden`_  algorithm for computing finite
  semigroups which act on sets.

``libsemigroups_pybind11`` is a python package exposing much (but not all) of
the functionality of ``libsemigroups``. 

The development version of ``libsemigroups_pybind11`` is available on github_,
and some related projects are here_.

.. _github: https://github.com/libsemigroups/libsemigroups_pybind11
.. _here: https://github.com/libsemigroups 

.. _Froidure-Pin algorithm: https://www.irif.fr/~jep/PDF/Rio.pdf
.. _Todd-Coxeter algorithm: https://en.wikipedia.org/wiki/Todd%E2%80%93Coxeter_algorithm
.. _Knuth-Bendix algorithm: https://en.wikipedia.org/wiki/Knuth%E2%80%93Bendix_completion_algorithm
.. _Schreier-Sims algorithm: https://en.wikipedia.org/wiki/Schreier%E2%80%93Sims_algorithm
.. _Konieczny: https://link.springer.com/article/10.1007/BF02573672
.. _Lallement-McFadden: https://www.sciencedirect.com/science/article/pii/S0747717108800570 

How to use it
~~~~~~~~~~~~~

See the installation instructions:

.. toctree::
   :maxdepth: 1
  
   install
   changelog

.. toctree::
   :caption: API REFERENCE
   :hidden:

   congruences
   digraph
   elements
   fpsemigroups
   semigroups
   words
   misc

.. toctree::
   :caption: Bibliography
   :hidden:

   biblio

.. toctree::
   :caption: Further info
   :maxdepth: 1
  
   authors
